# ufs_workflows_sandbox
A repository to collaborate with HAFS folks and NCAR CGD folks, among others, regarding the infrastructure HSUP project.

## To obtain the UFS hurricane application:
git clone https://github.com/NCAR/ufs_workflows_sandbox  
cd ufs_workflows_sandbox  
./manage_externals/checkout_externals -e Externals.hurricane.cfg  

## Governance

### Purpose

The purpose of the UFS workflows sandbox (hereafter referred to as “the sandbox”) is 1) to bring together common workflow tools and source codes into a single location for the purpose of facilitating workflow development in the UFS by project team members and relevant community partners; and 2) to provide a collection point for requirements for the UFS hurricane application workflow in particular and other UFS application workflows in general.

### Procedures for performing code development work

1. The sandbox itself simply links to workflow tools and source codes in various other repositories via manage_externals. If you wish to perform code development in those repositories, please coordinate with their respective code managers directly.

2. If you believe your external development advances the capabilities of tools or source codes for UFS workflows and would like to add it to the sandbox, please let the sandbox manager know. S/he will work with you to understand your development(s) and inform other sandbox members.

3. If there is agreement from other members, the sandbox manager will add an external that points to the branch or fork that contains your development so others can use it.

4. Currently, the sandbox only contains an Externals.cfg file for the UFS hurricane application workflow. If you would like to add an Externals.cfg file for another UFS application’s workflow, please prepare a draft of the file with the appropriate externals and send it to the manager to review. S/he will share it with other members of the group, provide any feedback to the requestor, and commit it to the repository.

### Process for submitting and reviewing UFS workflows requirements

1. Each person who wishes to contribute to setting requirements for UFS workflows (including the hurricane application) should first login to their GitHub account or obtain an account if they don’t already have one. The preferred syntax for GitHub usernames is FirstLast-NOAA (or your organization), but there is no need to change existing GitHub usernames.

2. Navigate to https://github.com/NCAR/ufs_workflows_sandbox/issues

3. Click the green “New issue” button in the upper-right corner.

4. Give your issue a descriptive title name.

5. In the “leave a comment” box, describe what you would like the hurricane application workflow (or other UFS application workflow) to be able to do (or not do). You can be as detailed or general as you would like, and your comment can span many different aspects of workflows, such as the workflow configuration manager (e.g., rocoto, ecFlow), the scripts, the configuration files, etc.

6. OPTIONAL: In the column on the right, click on “labels” and assign any labels that relate to the nature of your requirement.

7. Click “submit new issue.” You’re done!

8. Your feedback will be summarized at the review of the Configuration manager for Research and Operational Workflows (CROW) software and will be used to determine if CROW can meet the requirements to be implemented in the hurricane application. It will also be shared with the relevant UFS application team(s) to inform the workflow development process.

### Status of this Governance

This governance is a living document and will be updated as the sandbox and related UFS workflow projects evolve.

Last updated: December 31, 2019

### Point of Contact

Please direct questions or comments about this governance policy or the UFS workflows sandbox to Evan Kalina (Firstname.Lastname@noaa.gov), sandbox manager.

