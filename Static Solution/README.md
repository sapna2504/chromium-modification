# Modifications
We have modified the following four files in [chromium](https://github.com/chromium/chromium/) codebase:
- net/http/alternative_service.cc
- net/http/broken_alternative_services.cc
- net/http/http_stream_factory_job_controller.cc
- net/quic/quic_context.h

We have also added the patch file named `modifications.patch`

# Sample Files
### Application and Network logs (chrome/chromium)
1. in-the-wild (only network logs)
2. real-traces (both)
3. original vs modified (both)
4. dynamic-high (both)
5. dynamic-low (both)
6. dynamic-very-low (both)

Also, we have uploaded the application and network logs of mozilla firefox under dynamic-very-low bandwidth pattern.

### Application and Network logs (geographical locations) 
1. delhi
2. bangalore
3. new-york
4. singapore
5. germany

# Real World Trace Files
In addition, we have uploaded mahimahi trace files generated from the real pcaps.
