### Project: FApro

**Overview**:
FApro seeks to improve the quality of life of financial advisors (FAs). It allows FAs to keep track of large numbers of contacts. It allows FAs to have a one-stop platform to manage their contacts and conduct financial analytics while providing a big-picture view of their clientele as a whole.

Given below are my contributions to the project.

* **New Feature**: Added the ability to undo certain commands: `undo`
    * What it does: Allows the user to undo the most recent command. Only commands that modify the addressbook, such 
      as `add`, `clone`, `edit`, `delete` & `clear` can be undone. 
    * Justification: As financial advisors, or users in general, may make mistakes from time to time, undo provides 
      a simple way to undo such mistakes without having to use more commands.
    * Highlights: This was my first major change/contribution. I struggled to implement it at the start, but I 
      slowly learnt how to trace the existing code in AB3 to understand how the different components acted together. 
      As this feature went through multiple (painful) iterations, I gained more experience on writing test cases as 
      well as got more familiarised with the code structure. 



* **Code contributed**: [RepoSense link](https://nus-cs2103-ay2324s1.github.io/tp-dashboard/?search=glenngnng&breakdown=false&sort=groupTitle%20dsc&sortWithin=title&since=2023-09-22&timeframe=commit&mergegroup=&groupSelect=groupByRepos)



* **Project management**:
  * (fill in later)


* **Enhancements to existing features**:
  * For undo to work, I needed to store certain information when commands such as `add`, `clone`, `edit`, `delete` & 
    `clear` were executed.
    * For `add` & `clone`, I added a functionality that stored which contact was being added.
    * For `edit`, I added a functionality that stored both the original `Person` and the edited `Person`.
    * For `delete` & `clear`, I added a functionality that stored the deleted `Person`s.


* **Documentation**: 
  * User Guide:
    * Added documentation for the `undo` feature.
    * Updated documentation for `delete` and `clear` features. 
  * Developer Guide:
    * Added implementation of the `undo` feature.

* **Community**:
  * (fill in later)


    
    
    
