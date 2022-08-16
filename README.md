# CMPG-323-Overview--34570888
This will be my overview for my CMPG 323 project(s).
For the successful completion of this module I will need to complete the following tasks:
# Project 1 (Agile & Scrum)
* Create project repository
* Introduction to Agile & Scrum
* Introduction to Source Control
* Create GitHub project
* Create GitHub Overview Repository
* Source Control training
* Create Project Views
* Populate Project Tabular View
* Create Project Charts
* Link Repository to Project 1
* Git & Scrum Certifications
* Submit Project 1
# Project 2 (API Development)
* Create project repository
* Introduction to Cloud
* Introduction to APIs
* Join Microsoft Community
* Azure Fundamentals training
* API Development training
* Cloud Certification
* Submit Project 2
# Project 3 (Web App Project Testing Patterns)
* Create project repository
* Introduction to Design and Architecture Patterns
* Web Application Development training
* Submit Project 3
# Project 4 (Robotic Process Automation & Testing Project)
* Create project repository
* Introduction to Testing
* Join UiPath Community
* Robotic Process Automation training
* Automation & RPA Certification
* Submit Project 4
# Project 5 (Reporting Project)
* Create project repository
* Introduction to Reporting/Data Visualisation
* Power BI - Visualisation training
* Data Visualisation Certification
* Submit Project 5

## The branching strategy to be used in each project:
* I plan on using the **GitHub Flow** branching strategy for all my projects since it is a simpler alternative to GitFlow and I believe it will be ideal for me when I work on my project(s) since I won't need to manage multiple versions.
With this model, I will start off with a main branch in all my projects then I will create branches that will stem directly from the master to isolate my work which will be merged back into main when I'm done. The "develop" branch will then be deleted.
The main idea behind this will be to keep the master code in a constant deployable state to support continuous integration and continuous delivery processes.

## Explaining the use of a .gitignore file within each project:
* The use of a `.gitignore` file in my project(s) will be for files or folders that I don't want to commit to my project(s). Basically, it tells git which files to ignore when commiting my project(s) to the GitHub repository. This text file will be located in the root directory of my project(s).

## Explaining the storage of credentials and sensitive information:
* Storing sensitive information in GitHub is not really a good idea since data in GitHub is not encryted at rest and is easy to accidentally invite the wrong person. Although one can use `git-credential-store` to store their passwords unencrypted on the disk, where they will be protected only by the permissions of the file system. The credentials can be checked in the `~/.git-credentials`.
