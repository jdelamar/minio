## Current Release 
### 0.11.0 
**Release Date:** Wed Jun  5 16:34:48 UTC 2019     
## Previous Releases 
### 0.10.0 
**Release Date:** Fri Apr 26 15:42:33 UTC 2019     
* Upgrading to minio RELEASE.2019-04-18T21-44-59Z
### 0.9.0 
**Release Date:** Tue Apr 23 17:21:20 UTC 2019     
### 0.8.0 
**Release Date:** Mon Nov  5 14:38:52 UTC 2018     
* Upgrading to minio release RELEASE.2018-10-25T01-27-03Z
### 0.2.0 
**Release Date:** Fri Aug 31 19:33:18 UTC 2018     
### 0.1.0 
**Release Date:** Fri Aug 31 19:18:15 UTC 2018     
* Feature - Adding Accedian circle-ci, Changelog and Makefile changes
* Feature - Making the Health-check script value configurable. You can now use the STARTUP_GRACE_PERIOD_SEC env variable when starting this docker to set the time (in second) to wait before starting to perform actual healthcheck on a local minio server. This allows the minio cluster to stabilize before the healthcheck kicks people out.

