# Boss of the SOC (BOTS) Dataset Version 2
A sample security dataset and CTF platform for information security professionals, researchers, students, and enthusiasts. This page hosts information regarding the version 2 *Dataset*. If you would like access to the [CTF Scoreboard](https://github.com/splunk/SA-ctf_scoreboard) please visit [the CTF Scoreboard github page.](https://github.com/splunk/SA-ctf_scoreboard)

## Data Sourcetypes included
* access_combined
* activedirectory
* apache:error
* apache_error
* auditd
* bandwidth
* collectd
* cpu
* csp-violation
* df
* ess_content_importer
* hardware
* interfaces
* iostat
* lastlog
* linux:selinuxconfig
* linux_audit
* linux_secure
* ms:o365:management
* msad:nt6:health
* msad:nt6:siteinfo
* mysql:connection:stats
* mysql:database
* mysql:errorlog
* mysql:instance:stats
* mysql:server:stats
* mysql:status
* mysql:table_io_waits_summary_by_index_usage
* mysql:tablestatus
* mysql:transaction:details
* mysql:transaction:stats
* mysql:user
* mysql:variables
* mysqld-8
* netstat
* openports
* osquery_info
* osquery_results
* osquery_warning
* package
* pan:system
* pan:threat
* pan:traffic
* perfmon:cpu
* perfmon:logicaldisk
* perfmon:memory
* perfmon:network
* perfmon:network_interface
* perfmon:ntds
* perfmon:physicaldisk
* perfmon:process
* perfmon:processor
* perfmon:system
* powershell:scriptexecutionsummary
* protocol
* ps
* script:installedapps
* script:listeningports
* stream:arp
* stream:dhcp
* stream:dns
* stream:ftp
* stream:http
* stream:icmp
* stream:ip
* stream:irc
* stream:ldap
* stream:mysql
* stream:smb
* stream:smtp
* stream:tcp
* stream:udp
* suricata
* symantec:ep:agent:file
* symantec:ep:agt_system:file
* symantec:ep:behavior:file
* symantec:ep:packet:file
* symantec:ep:scan:file
* symantec:ep:scm_system:file
* symantec:ep:security:file
* symantec:ep:traffic:file
* syslog
* time
* top
* unix:listeningports
* unix:service
* unix:update
* unix:uptime
* unix:useraccounts
* unix:version
* userswithloginprivs
* vmstat
* web_ping
* weblogic_access_combined
* weblogic_stdout
* who
* windowsupdatelog
* wineventlog:application
* wineventlog:directory-service
* wineventlog:security
* wineventlog:system
* winhostmon
* winregistry
* xmlwineventlog:microsoft-windows-sysmon/operational

## Required Software
The dataset requires the following software which is distributed and licensed separately
and should be installed before using the dataset. The versions listed are
those that were used to create the dataset. Different versions of the software
may or may not work properly. If you are new to Splunk, follow [these instructions](http://docs.splunk.com/Documentation/Splunk/latest/Installation/Whatsinthismanual) to install the free Splunk Enterprise trial and [these instructions](https://docs.splunk.com/Documentation/AddOns/released/Overview/Singleserverinstall) to install apps and add-ons. 

| App / Add-on | Version | Download |
| ----------- | ------- | -------- |
| Splunk Enterprise                               | 7.2.0  | http://www.splunk.com
| SA-Investigator                                 | 1.3.1  | https://splunkbase.splunk.com/app/3749/
| Base64	                                        | 1.1	   | https://splunkbase.splunk.com/app/1922/
| URL Toolbox	                                    | 1.6	   | https://splunkbase.splunk.com/app/2734/
| Splunk Security Essentials                      | 2.3.0  | https://splunkbase.splunk.com/app/3435/
| JellyFisher	                                    | 0.1.0  | https://splunkbase.splunk.com/app/3626/
| Splunk Common Information Model	                | 4.12.0 | https://splunkbase.splunk.com/app/1621/
| Splunk Add-on for Apache                        | 1.0.0	 | https://splunkbase.splunk.com/app/3186/
| Splunk Add-on for Microsoft Cloud Services      | 2.0.3  | https://splunkbase.splunk.com/app/3110/
| Palo Alto Networks Add-on for Splunk            | 3.8.2	 | https://splunkbase.splunk.com/app/2757/
| Splunk Add-on for Symantec Endpoint Protection  | 2.3.0	 | https://splunkbase.splunk.com/app/2772/
| TA-Suricata	                                    | 2.3.3	 | https://splunkbase.splunk.com/app/2760/
| Microsoft Sysmon Add-on	                        | 6.0.4	 | https://splunkbase.splunk.com/app/1914/
| Collectd App for Splunk Enterprise              | 1.1    | https://splunkbase.splunk.com/app/2875/
| OSquery                                         |	1      | https://splunkbase.splunk.com/app/3278/
| SSL Certificate Checker                         | 3.2	   | https://splunkbase.splunk.com/app/3172/
| Website Monitoring	                            | 2.5    | https://splunkbase.splunk.com/app/1493/	
| Splunk Add-on for Microsoft IIS                 | 1.0.0	 | https://splunkbase.splunk.com/app/3185/
| Splunk Add-on for Unix and Linux                | 6.0.0  | https://splunkbase.splunk.com/app/833/
| Splunk Stream Add-on                            | 7.1.1  | https://splunkbase.splunk.com/app/1809/
| Splunk Add-on for Microsoft Windows             | 5.0.1  | https://splunkbase.splunk.com/app/742/


## Warning
**Please be advised that this datasets may contain profanity, slang, vulgar expressions, and/or generally offensive terminology. Please use with discretion.** 

This dataset contains evidence captured during actual computer security incidents, or from realistic lab recreations of security incidents. As such, the dataset **may** contain profanity, slang, vulgar expressions, and/or generally offensive terminology. The authors believe that the educational benefits of preserving the realism of the dataset outweigh the risk of offending some users. If the possibility of encountering this type of offensive material is a concern to you or to any audience with whom you plan to share the dataset, please stop now and do not continue.

## Authors
Written in 2017 by Ryan Kovar, David Herrald, James Brodsky, Jim Apger, Curtis Johnson, and David Veuve

## Copyright and License
To the extent possible under law, the author(s) have dedicated
all copyright and related and neighboring rights to this software
to the public domain worldwide. This software is distributed
without any warranty. You should have received a copy of the CC0
Public Domain Dedication along with this software. If not, see
http://creativecommons.org/publicdomain/zero/1.0/.
