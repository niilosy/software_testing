
## Summary (Summarize the bug encountered concisely)

I tried to create a new project on this page https://gitlab.com/projects/new#blank_project and was met with the usual options but I noticed that it said "create black project" on the page where options are "Create black project", "Create from template", "Import project" and "Run CI/CD for external repository". I've made projects through this page before and I am very sure it should read "Create blank project" for black project in this context makes no sense and the description reads "create blank project".

## Steps to reproduce     

Open the link https://gitlab.com/projects/new#blank_project or try to create a new project in git labs, you should encounter the bug on the page where you select the type of project you want to make the options listed above.   

## What is the current bug behavior?

The page reads "Create black project" as a title of an option, but in its description reads "Create a blank project to house your files etc."

## What is the expected correct behavior?

The options title should be "Create blank project"
     
## Relevant logs and/or screenshots

![alt text](image.png) here is the image and also the code found if image inaccessible "<h3 class="gl-text-size-h2 gl-text-inherit"> Create black project </h3>"

## Possible fixes

<h3 class="gl-text-size-h2 gl-text-inherit"> Create black project </h3>

"Create black project" should be replaced with "Create blank project"

## Whom do you report/ Assign To/ Tags

/label ~bug ~reproduced ~needs-investigation 
/cc @project-manager 
/assign @qa-tester

## Priority

It's minor priority I'd say, it only confuses the user a bit but the options meaning should still come across. Though it is a bit embarrasing...

      
