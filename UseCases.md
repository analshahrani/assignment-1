## USE CASE 1:

# Title: Determine License and Vulnerability Information of SW Packages.

1.Primary Actor: Corporate Manager

2.Goal in Context:The corporate manager is able to determine license and vulnerability from information from provided SW project information 

3.Stakeholders:
Corporate Manager: To receive clear and relevant project information 
Corporate Developer: To provide the relevant file/package information 
Project Owner: To clearly understand corporate manager decisions to green/red light a project 
NIST system: Provides Licence and vulnerability information of SW package 

4.Preconditions:
a. Relevant SW file/package information sent to be checked for OSS licences 
b. Proper project policy document has been provided to determine licence usage. 
c. Secure Internet connection is present. 
d. License and Vulnerability Database is up to date. 

5.Main Success Scenario:Corporate manager receives accurate license and vulnerability information for the requested project packages 

6.Failed End Conditions: Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages 

7.Trigger: Corporate Manager uploads SW project request to which license and vulnerability information is provided. 


## USE CASE 2:
# Title: Verify SW vulnerability of SW Packages.

1.Primary Actor: Corporate Developer 

2.Goal in Context: When corporate developer sends in SW package, he is provided with the SW vulnerability information.

3.Stakeholders: 
Corporate Developer: To receive the SW vulnerability information of the SW package. 

4.Preconditions:
a. Relevant SW file/package uploaded to Software Package manager
b. SW package manager is able to receive information from NIST database.
c. Secure Internet connection is present. 

5.Main Success Scenario: Corporate Developer receive accurate SW vulnerability information from NIST Datastore.

6.Failed End Conditions: SW vulnerability information of the SW package is not obtainable from the NIST Datastore.

7.Trigger:  Corporate Developer sends in SW package.


## USE CASE 3:
# Title:Modify Corporate SW licence policy documents 

1.Primary Actor: Corporate Manager

2.Goal in Context: Corporate manager is able to modify or create corporate SW licence policy documents  

3.Stakeholders: 
Corporate Manager: To receive or create corporate SW licence policy information 
SW Package licence and vulnerability policy database: To provide the relevant SW licence policy information 

4.Preconditions: 
a. Relevant Policy document uploaded to SW licence policy information 
b. Secure Internet connection is present. 

5.Main Success Scenario: Accurate SW licence policy information is provided to Corporate manager to make informed decisions

6.Failed End Conditions: Create or update of SW licence policy documents is not being able to be performed by Corporate manager to make informed decisions

7.Trigger: Corporate manager creates or updates SW policy documents for the corporate policy Datastore.

