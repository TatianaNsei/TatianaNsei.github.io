---
layout: post
title: "Version Control"
date: 2020-04-09
---

# Understanding Version Control

Also known as revision control or source control, version Controls is all about the management of changes to documents, 
large websites, computer programs and other collections of information. Version control is a system that records changes 
to a file or set of files over time so that you can recall specific versions later.
   Thus we can summerise it this way.It lets you track your files over time, So incase you mess up you can easily get back 
to a previous working version. Simple Right!


# It's Importance

Now that we understand what this version control is, its neccessary that we know why we need it that is, how useful it can be.
If you are a graphic or web designer and want to keep every version of an image or layout, a Version Control System (VCS) is a very wise thing to use. It allows you to revert selected files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Remember using a VCS also generally means that if you screw things up or lose files, you can easily recover. In addition, you get all this for very little overhead. 
 
 For a novice, when you work on a file and save it, its the first version revision1. You might later on, modify it this gives it another version say revision2. But then, revision1 might have important content you dont want to alter and not neccessary in revision2, we use "save as". It’s why we use “Save As”. You want the new file without obliterating the old one. Lateron, these revisions can be compared, restored, and with some types of files, merged.
  
  For professional developers, it goes futher. Software developers, use this to tract and provide control over source codes. As teams design, develop and deploy software, it is common for multiple versions of the same software to be deployed in different sites and for the software's developers to be working simultaneously on updates. Bugs or features of the software are often only present in certain versions (because of the fixing of some problems and the introduction of others as the program develops). Therefore, for the purposes of locating and fixing bugs, it is vitally important to be able to retrieve and run different versions of the software to determine in which version(s) the problem occurs. It may also be necessary to develop two versions of the software concurrently: for instance, where one version has bugs fixed, while the other version is where new features are worked on. 

  
 # Examples of Version Control Systems (VCS)
  
   There exist many VCS options, but i will name a few here.

## **a) GitHub**

It helps software teams to collaborate and maintain the entire history of code changes. You can track changes in code, turn back the clock to undo errors and share your efforts with other team members.
It is a repository to host Git projects. For those wondering what is Git? It is an open source version control system that features local branching, multiple workflows, and convenient staging areas. Git version control is an easy to learn option and offers faster operation speed.

## * *Pros*

*Easy and inexpensive branch operations

*Users can access the complete history tree offline

*It offers a highly distributed, peer-to-peer model

## * *Cons*

*Not ideal for developers working alone

*Limited support for Windows in comparison to Linux

## **b) Mercurial**

Mercurial is known for its efficiency in handling projects of all sizes. It is a free and distributed control management service that provides a simple and intuitive user interface.
Developers and enterprises adore Mercurial for its backup system, search functionality, project tracking and management, data import and export, and data migration tool. It also features workflow management, history tracking, security management, access controls and more.

## * *Pros*

*Low learning curve compared to Git

*Extensive and better documentation

*Highly distributed model

*High-performance system with great speed

## * *Cons*

*Cannot merge two parents

*It is more based on extension rather than scripting

*Not versatile enough to allow out-of-the-box maneuvers

## **c) CVS**

CVS is the most popular and widely adopted revision control system to date. It has gained popularity mainly because of the low learning curve and its simple system to keep files and revisions up to date.
There is an array of IDEs for CVS including Xcode (Mac), Eclipse, NetBeans and Emacs all of which use CVS.

## * *Pros*

*It is a time-tested and mature system which has been in use for more than three decades.

*There are a lot of IDEs that use CVS.

## * *Cons*

*When you move or rename files it is not included in the version update

*Offering symbolic links to files involves some security risks

*Absence of any support for atomic operation can lead to corruption of source code

*Very slow tagging and branch operation
  
## **d) GitLab**

GitLab comes with a lot of handy features like an integrated project, a project website, etc. Using the continuous integration (CI) capabilities of GitLab, you can automatically test and deliver the code.

You can access all the aspects of a project, view code, pull requests, and combine the conflict resolution.

## **e) Beanstalk**

Beanstalk is an ideal option for those who need to work from remote places. This software is based on browser and cloud, allowing users to code, commit, review and deploy using a browser.
It can be integrated with messaging and email platforms for efficient collaborations related to codes and updates. It supports both Git and SVN and comes with built-in analytics features.

For security, it leverages encryption, two-factor authentication, and password protection functionalities.

## **f) PerForce**

Perforce delivers the version control capabilities through its HelixCore. The HelixCore comes with a single platform for seamless team collaboration, and support for both centralized and distributed development workflows.

It is a security solution that protects the most valuable assets. HelixCore allows you to track the code changes accurately and facilitates a complete Git ecosystem.



# **Pros and Cons of using Version Control Softwares (VCS)**
  
 ## * *Pros*
  
    *Streamlining the development process, management of code for multiple projects and keeping a history of all changes within a code is one of the main importance of using VCS
 
 *A VCS saves all the changes in a repository. So, if the developers make a mistake, they can undo it. This reduces human errors and unintended consequences to a great extent. 
  
  *Developers can combine the code changes when required. Further, they can view the history of changes, go back to the previous version(s) and use/manage code in the desired fashion. 
  
  *VCS can be integrated with several software development tools like PaaS providers, integrated development environments (IDE) and build automation tools.
 
## * *Cons*

  *It may not always be obvious who did the most recent change fordistributed CVS.
  
  *For a centralised CVS if the central database is corrupted, the entire history could be lost (security issues).
  
  *File locking doesn’t allow different developers to work on the same piece of code simultaneously. It helps to avoid merge conflicts, but slows down development
