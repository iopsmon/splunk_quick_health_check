Splunk Quick Health Check App

This apps provides a quick health assessment of the Splunk enviroment and some basic statistics. Its useful during Splunk delivery and where the Splunk Monitoring Console has not been factored into the solution. The app also provides a dashboard which shows all Splunk managed assets and source types.

Dashboard Features:

    Quick overview of the enviroments health
    Index and Indexer health
    Disk capacity health
    Search health
    Queues health
    Inventory
    Troubleshooting help
    ES health (Only for ES based environments)
    DMA health
    Compute health
    Internal Logs Check 
    Data Quality Checks 




![](images/health.jpg)

Config:

Update the macros.conf with your indexers and search heads, see macros.conf in the default, make a copy in the local folder and update

Installation Guide:

Install this on the MC server

    Download the zip and extract the file, copy the DC_splunk_quick_health to the Splunk Server
    sudo cp -R DC_splunk_quick_health /opt/splunk/etc/apps
    sudo chown -R splunk:splunk /opt/splunk/etc/apps
    sudo -u splunk /opt/splunk/bin/splunk restart
