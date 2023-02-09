App Developer: Deepak Chohan - app not supported 
=======================================================================
[Install Steps] 
Task 1  Install this ap onto the Slunk SH / SHC / AIO as admin
tar -cvf DC_splunk_quick_health.tar -C /opt/splunk/etc/apps 
OR use the GUI method
=======================================================================
=======================================================================

[Config Steps] 
Task 1 Configure macros.conf - these are required as per your enviroment

Add your license limit - eg 100
[my_lic_limit]]

Add your indexers for OS disk space check eg splunk_servers=idx*
[my_idx_servers]

Add  your indexers hosts  eg splunk_servers=idx*
[my_idx_hosts]

Add your search head to check for users login, eg splunk_servers=sh*
[my_sh_servers]

Add all your Splunk servers 
[my_sh_servers]
=======================================================================
 
