
## Summary (Summarize the bug encountered concisely)
In the url = https://gitlab.com/projects/new "Create a new project" page is a typo bug.
The typo is on the title of the "Create blank project" section and it says "black project" instead of "blank project".

## Steps to reproduce
Steps:
1. Navigate to the url = https://gitlab.com/projects/new
2. Look for the "Create blank project" option
3. Observe the typo on the options title.
   
## What is the current bug behavior?
The bug behaviour is a static text on the option that incorrectly reads "Create black project," causing confusion for trying to find this option.

## What is the expected correct behavior?
The correct behaviour is to display the correct title of the "Create blank page" option.

## Relevant logs and/or screenshots
screenshot of the incorrect title:

![alt text](../Image/Bug_Project_create_blank.png)

## Possible fixes
Here is the line of code of the problem:

<h3 class="gl-font-size-h2 gl-reset-color">
    Create black project
</h3>

## Whom do you report/ Assign To/ Tags
/label ~bug ~reproduced ~needs-investigation 
/cc @project-manager 
/assign @qa-tester

## Priority
Major priority, because it causes confusion for the user.