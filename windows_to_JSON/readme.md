NXLOG Configuration Files
======================

nxlog config file to convert Windows Event Logs and IIS Logs to JSON

Usage
-----

To use this tool:

1.  Download this file and place it in your NXLog conf directory.
2.  Make sure to replace ROOT variable if necessary.
3.  You will need to make 1 instance of each IIS_Site for each site - and update the 
logical path to the files
	
Files
------

nxlog.conf = for general usage with Windows Agent
nxlogdh.conf = for use with DataHub	