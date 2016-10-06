#USE CASE 1:
<b>Title:</b> Determine License and Vulnerability Information of SW Packages.
<b>1.Primary Actor:</b> Corporate Manager
<b>2.Goal in Context:</b> The corporate manager is able to determine license and vulnerability from information from provided SW project and project information 
<b>3.Stakeholders:</b> 
Corporate Manager: To receive clear and relevant project information 
Corporate Developer: To provide the relevant file/package information 
Project Owner: To clearly understand corporate manager decisions to green/red light a project 
NIST system: Provides Licence and vulnerability information of SW package 
<b>4.Preconditions:</b>
a. Relevant SW file/package information sent to be checked for OSS licences 
b. Proper project policy document has been provided to determine licence usage. 
c. Secure Internet connection is present. 
<b>5.Main Success Scenario:</b> Corporate manager receives accurate license and vulnerability information for the requested project packages 
<b>6.Failed End Conditions:</b> Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages 
<b>7.Trigger:</b> Corporate Developer/Manager uploads SW package to which license and vulnerability information is provided. 


#USE CASE 2:
<b>Title:</b> Manage SW project Information	 
<b>1.Primary Actor:</b>  Corporate Manager 
<b>2.Goal in Context:</b> The OSS licence database check process interacts with the resources in the internet to find OSS components in the SW package
<b>3.Stakeholders:</b> 
Corporate Manager: To receive clear and relevant project information 
Corporate Developer: To provide the relevant file/package information 
<b>4.Preconditions:</b> 
a. Relevant SW file/package uploaded to Software Package manager. 
b. Secure Internet connection is present. 
<b>5.Main Success Scenario:</b> OSS licence information of the SW package is obtained from resources in internet and passed on to SW package manager. 
<b>6.Failed End Conditions:</b> OSS licence information of the SW package is not obtainable from available resources in the internet and so not data is passed on to SW package manager
<b>7.Trigger:</b>  Developer/Manager uploads SW package to SW package manager



#USE CASE 3:
<b>Title:</b> Manage SW project Information	 
<b>1.Primary Actor:</b>  Corporate Manager
<b>2.Goal in Context:</b> Corporate manager is provided with the requested OSS licence information for a given SW package
<b>3.Stakeholders:</b> 
Corporate Manager: To receive clear and relevant project information 
NIST: To provide the relevant SW package vulnerability information 
OSS Package Datastore: Provides OSS licences Datastore
<b>4.Preconditions:</b> 
a. Relevant SW file/package uploaded to Software Package manager. 
b. Secure Internet connection is present. 
<b>5.Main Success Scenario:</b> Accurate OSS licence information of the SW package is provided to Corporate manager to make informed decisions
<b>6.Failed End Conditions:</b> Inaccurate or no OSS licence information of the SW package is provided to Corporate manager to make informed decisions
<b>7.Trigger:</b>  Corporate manager provides SW package request to the system.
