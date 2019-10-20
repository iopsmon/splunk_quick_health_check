#test
splunk_quick_health_check

Splunk Quick Health Check App

This apps provides a quick health assessment of the Splunk enviroment and some basic statistics. Its useful during Splunk delivery and where the Splunk Monitoring Console has not been factored into the solution. The app also provides a dashboard which shows all Splunk managed assets and source types.

Features:

    Average Indexed Data Per Day
    Dispatcher Que Stats
    Total Event Count
    Licence Usage
    Average EPS
    GB Volume Limit Chart
    Users Logged Into Splunk
    Splunk Restart Events
    Splunk Server File System Usage
    Splunk Memory And Cpu Usage
    Cluster Events Splunkd Log
    Indexed Data Per Day
    Top 10 Forwarders By MB
    Indexer Retention Days
    License Usage By Sourcetype
    Forwarder Status
    Index Sizes
    Index Age
    Sourcetypes
    Inventory
    Users And Roles
    indexing Queue Sizes
    Search Duration Analysis
    Skipped Searches
    Datamodel Details
    Top Sourcetypes

Config:

    Change the 'License Usage' widget search to inlude your license server
    Change the splunk server instance in the 'Index Age' search widget

Install:

    Download the zip and extract the file, copy the DC_splunk_quick_health to the Splunk Server
    sudo cp -R DC_splunk_quick_health /opt/splunk/etc/apps
    sudo chown -R splunk:splunk /opt/splunk/etc/apps
    sudo -u splunk /opt/splunk/bin/splunk restart
