Config Steps 
Task 1 Configure macros.conf 

Add your license limit - eg 100
[my_lic_limit]]

Change the splunk server to your indexers for OS disk space check eg splunk_servers=idx*
[my_idx_servers]


Change the splunk server to your search head to check for users login, eg splunk_servers=sh*
[my_sh_servers]


 
