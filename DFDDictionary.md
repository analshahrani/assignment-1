This file holds all definitions about the DFD Diagram.


## External Entities:

• National Vulnerability Database: National Institute of Standards and Technology's (NIST): NVD is the U.S. government repository of standards based vulnerability management data represented using the Security Content Automation Protocol(SCAP). This data enables automation of vulnerability management, security measurement, and compliance. NVD includes databases of security checklists, security related software flaws, misconfigurations, product names, and impact metrics.

• OSS Community: Represents open source repositories to which source code taken from the community is re-published.

•	SW Package Licence and vulnerability policy database: Data store that holds the company's policy information.

•	OSS Package Datastore: It is a Datastore that holds the results of licence information of OSS components in an SW package.

## Internal Entities:

•	Corporate Developer: Usually a technical person (Software Developer) who is developing the software package.

•	Software Package Manager:  It is a process which is used to detect OSS components in the developed Software package. It interacts with the internet to verify if the SW package has any OSS components

•	OSS Licence Database check: It is a process to take the SW package and search the internet for OSS licence associated with the SW package.

•	OSS Package Datastore: It contains the repository of OSS components licence information.

•	Corporate Manager: The manager is the individual who oversees the whole project. He can submit SW package requests like a developer. He can also submit a SW package and submit or modify policy documents.

•	SW package licence and vulnerability policy database: It is a database, where corporate policy as to what are acceptable licences and vulnerability thresholds.

## Data Flow:

•	OSS Licence and vulnerability Info: It is the report on Open Source software components in the SW package requested.

•	SW Package: It is the collection of SW submitted in the system to be checked for OSS components.

•	SW Vulnerability Info: It is the vulnerability information from NIST on the submitted SW Package name.

•	OSS Licence Information:  It is the OSS components licence information for the OSS components in SW package.

•	SW Project: It is a collection of SW packages.

•	Project Policy Document: It is the policy document that is to be added or modified in the Policy database. Only corporate managers have the rights to submit or edit an existing policy. 

•	Updated policy document: It is the updated policy document that is taken from policy database of the company. It had been modified or added by a corporate manager. 

•	Project Policy request: It is the project request is set against an open source policy document to highlight software packages that violate license or vulnerability requirements.

•	Policy Info: It is the policy information related to the project request sent by a corporate manager.

 

## Processes:

•	Developer submits SW package for which the he receives information regarding its licences, software vulnerabilities etc. He submits it to accepts software package process.

•	Software Package Manager accepts SW package from accept software package process and sends it to OSS Licence Database check process.

•	SW package manager sends the SW package name to NIST Database and OSS Licence Database Check process.

•	NIST Database reports the SW vulnerability information of SW package to Software package manager.

•	OSS Licence Database check receives SW package and reports the OSS Licence Information to software package manager.

•	The OSS licence and vulnerability info is stored in OSS Package Datastore after it is obtained from Software Package manager. 

•	Developer and manager individually submit project policy request via OSS policy referral process to SW Package Licence and vulnerability policy database.

•	Project policy document is sent by manager to the SW Package Licence and vulnerability policy database to Add, Edit or Modify the contents of the policy documents via Modify/Add/Edit policy documents process.

•	Developer and manager can submit SW project information to OSS Package Datastore via Manage SW project information process to obtain its OSS licence and vulnerability information.


	 




