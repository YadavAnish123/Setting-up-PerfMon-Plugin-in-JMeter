Step 1 : Add perfmon plugin in JMeter
   1. Download and add to JMeter lib and ext folder    https://jmeter-plugins.org/wiki/PerfMon/
   2. Plugins Manager

Step 2 : On server
   Download perform server agent   https://github.com/undera/perfmon-age...

Step 3 : Start the perfmon server agent
   Mac/linux - terminal - sh startAgent.sh
   Windows - startAgent.bat

   Check client can talk to server via port 4444

Step 4 : Create JMeter test to monitor Server Health

Step 5 : Run and Validate
