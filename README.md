# check_cisco_uc_perf
check_cisco_uc_perf is a Nagios plugin to monitor the performance of Cisco Unified Communications Servers


file: check_cisco_ucm_perf.go
Version 0.3 (27.02.2015)

check_cisco_ucm_perf is a Nagios plugin made by Herwig Grimm (herwig.grimm at aon.at)
to monitor the performance Cisco Unified Communications Manager CUCM.

I have used the Google Go programming language because of no need to install
any libraries.

The plugin uses the Cisco PerfmonPort SOAP Service via HTTPS to do a wide variety of checks.

This nagios plugin is free software, and comes with ABSOLUTELY NO WARRANTY.
It may be used, redistributed and/or modified under the terms of the GNU
General Public Licence (see http://www.fsf.org/licensing/licenses/gpl.txt).

# tested with: 	Cisco Unified Communications Manager CUCM version 9.1.2.11900-12
				Cisco Unified Communications Manager CUCM version 8.6.2.22900-9

# see also:
 		Cisco Unified Communications Manager XML Developers Guide, Release 9.0(1)
 		http://www.cisco.com/c/en/us/td/docs/voice_ip_comm/cucm/devguide/9_0_1/xmldev-901.html

# changelog:
		Version 0.1 (15.05.2014) initial release
		Version 0.2 (20.05.2014) object caching added. new func loadStruct and saveStruct
		Version 0.3 (27.02.2015) General Public Licence added