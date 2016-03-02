# satperf

#satperf: What does it have? 

This started a project to run performance tests on Redhat Satelitte.
satperf need to be run from Satelitte server. It contains

 Satelitte install
 upload manigfest, update repo
 concurrently sync multiple Repositories from Repo Server
 create lifecycle environments
 create capsules
 concurrently  syncronize multiple capsules
 ..etc

 
 Measure time for all while capturing resources using pbench. 
 https://github.com/distributed-system-analysis/pbench

#Before Running satperf
Make sure to update satperf.cfg which contains details like RHN_USERNAME, 
RHN_PASSWD, pool_id, capsule names. 

Update PBENCH_REPO and  install pbench using pbench/install_pench.sh on 
required nodes. ./pbench/install_pbensh.sh  

And also make sure to copy public keys of satelitte server and capsules 
amond them. 