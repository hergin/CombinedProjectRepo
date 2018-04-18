# CombinedProjectRepo

In the repository, I have analyzed how two projects in a single repo will look like. Here are the steps in IntelliJ Idea. However, this is not endorsed. Don't forget: One project per repository is a better approach.

- I created a folder called “MyCombinedProject”.
- I created an intellij java project in this folder called “JavaProject”
- I created another intellij idea project in the same folder called “AnotherJavaProject”
- I opened one of the projects and go to menu “VCS>>Import Into Version Control” and I selected the root folder, which is “MyCombinedProject”
- Now the rest is the same for this project, like adding remotes, committing and pushing/pulling etc.
- When you open the other project on intelliJ though, it will complain about some “Unregistered VCS root detected”. In this case, you can click “Configure” and select the root folder again as a repository.
- Now all two projects are good and can be pushed/pulled through intellij.
