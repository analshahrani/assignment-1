#USE CASE 1:
<b>Title:</b> Determine License and Vulnerability Information of SW Packages 
1.Primary Actor: Corporate Manager
 2.Goal in Context: The corporate manager is able to determine license and vulnerability from information from provided SW project and project information 
3.Stakeholders: 
Corporate Manager: To receive clear and relevant project information 
Corporate Developer: To provide the relevant file/package information 
Project Owner: To clearly understand corporate manager decisions to green/red light a project 
NIST system: Provides Licence and vulnerability information of SW package 
4.Preconditions:
a. Relevant SW file/package information sent to be checked for OSS licences 
b. Proper project policy document has been provided to determine licence usage. 
c. Secure Internet connection is present. 
5.Main Success Scenario: Corporate manager receives accurate license and vulnerability information for the requested project packages 
6.Failed End Conditions: Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages 
7.Trigger: Corporate Developer/Manager uploads SW package to which license and vulnerability information is provided. 


#USE CASE 2:
Title: Manage SW project Information	 
1.Primary Actor:  Corporate Manager 
2.Goal in Context: The OSS licence database check process interacts with the resources in the internet to find OSS components in the SW package
3.Stakeholders: 
Corporate Manager: To receive clear and relevant project information 
Corporate Developer: To provide the relevant file/package information 
4.Preconditions: 
a. Relevant SW file/package uploaded to Software Package manager. 
b. Secure Internet connection is present. 
5.Main Success Scenario: OSS licence information of the SW package is obtained from resources in internet and passed on to SW package manager. 
6.Failed End Conditions: OSS licence information of the SW package is not obtainable from available resources in the internet and so not data is passed on to SW package manager
7.Trigger:  Developer/Manager uploads SW package to SW package manager



#USE CASE 3:
Title: Manage SW project Information	 
1.Primary Actor:  Corporate Manager
2.Goal in Context:  Corporate manager is provided with the requested OSS licence information for a given SW package
3.Stakeholders: 
Corporate Manager: To receive clear and relevant project information 
NIST: To provide the relevant SW package vulnerability information 
OSS Package Datastore: Provides OSS licences Datastore
4.Preconditions: 
a. Relevant SW file/package uploaded to Software Package manager. 
b. Secure Internet connection is present. 
5.Main Success Scenario: Accurate OSS licence information of the SW package is provided to Corporate manager to make informed decisions
6.Failed End Conditions: Inaccurate or no OSS licence information of the SW package is provided to Corporate manager to make informed decisions
7.Trigger:  Corporate manager provides SW package request to the system.

