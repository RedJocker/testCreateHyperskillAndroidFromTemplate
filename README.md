# project-android-template

This project is a template for any hyperskill android project you want to create.

## Getting Started

On AndroidStudio 
File -> New -> Project From Version Control -> 
    Url: https://github.com/hyperskill/android-projects-template.git

Git -> Manage Remotes -> click origin -> remove
Git -> Manage Remotes -> add -> Url: <make-a-new-github-repository-and-link-it-here.git>  

change Course tab to Project tab -> right click 'Project Name' folder  -> refactor -> rename  

also with right click methods rename test/java/org/hyperskill/projectname and main/.../projectname obs: all lowercase and without separators

On AndroidManifest.xml change _package_, make sure _activity name_ has already changed 

On course-info.yaml change _title_ and make sure _content_ has already changed

On module build.gradle, which is the one under stage1 folder, change _applicationId_

On Commit tab add every file, write message "Project Name initial commit" -> commit and Push
 