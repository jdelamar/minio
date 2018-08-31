## Current Release 
### 0.2.0 
**Release Date:** Fri Aug 31 19:33:18 UTC 2018     
## Previous Releases 
### 0.1.0 
**Release Date:** Fri Aug 31 19:18:15 UTC 2018     
* Feature - Adding Accedian circle-ci, Changelog and Makefile changes
* Feature - Making the Health-check script value configurable. You can now use the STARTUP_GRACE_PERIOD_SEC env variable when starting this docker to set the time (in second) to wait before starting to perform actual healthcheck on a local minio server. This allows the minio cluster to stabilize before the healthcheck kicks people out.

