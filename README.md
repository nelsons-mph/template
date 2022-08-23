# java-app-repo-template

<details> 

<summary> Repo naming conventions recommended by GitHub  </summary>
<br>
Well there aren't any conventions specified by Git and GitHub, it is always good to follow some rules and conventions to create a new branch, its flow etc. In general, Git branches fall into two different categories:
       <li> 1. Regular/Evergreen branches
       <li> 2. Temporary branches
<br>

<b> Regular Git branches </b>

<br>
These branches will be available in your repository on permanent bases. Their naming convention is simple and straightforward.

<br>
<li> Development (dev) is the main development branch. The dev branch’s idea is to make changes in it and restrict the developers from making any changes in the master branch directly. Changes in the dev branch undergo reviews and, after testing, get merged with the master branch.


<li> Main (main, yes main and not <strike> master</strike>)  is the default branch available in the Git repository. It should be stable all the time and won’t allow any direct check-in. You can only merge it after code review. All team members are responsible for keeping this stable and up-to-date.


<li> QA (QA), or test branch, contains all the code for QA testing and automation testing of all changes implemented. Before any change goes to the production environment, it must undergo the QA testing to get a stable codebase.
<br>

<br>
<b> Temporary Git branches </b> 

<br>
As the name indicates, these are the branches that can be created and deleted when needed. They can be as follows:
    <li> Bug Fix
    <li> Hot Fix
    <li> Feature Branches
    <li> Experimental Branches
    <li> WIP branches
</details>

<br>

Template repositories with an automation template that includes
  1. Tags
  2. Recommended Branches
  3. Access settings
  4. Review settings
  5. Team settings
