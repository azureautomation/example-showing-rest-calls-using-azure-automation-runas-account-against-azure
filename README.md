Example showing REST calls using Azure Automation RunAs account against Azure
=============================================================================

            




Example showing REST calls using Azure Automation RunAs account against Azure resources (automation runbook job)

You could publish the below code as a new python runbook (hello_world_python) and then start it with this sample.

#!/usr/bin/env python2
import getopt
import sys

opts, args = getopt.getopt(sys.argv[1:], 'n:')
for o, a in opts:
    if o == '-n':
        name = a


print 'Hello ' + name

**






 




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
