# demo-Jenkinsfile
Jenkinsfile for the demo pipelines and practice challenges I created.

## challenge 1
It's a really simple pipeline which includes 6 stages.
1st stage is the Clean up stage. It is not necessary but I include it as a good practice.
2nd-6th stages include a message "Hi! from stage X" where X is the stage number starting from 1.

## demo-declarative-pipeline
Pipeline contains 4 stages.
1st : Clean Up stage
2nd : Clone Repo stage where I clone a public repo from Github.
3rd : Build stage where I invoked the maven install phase.
4th : Test stage where I invoke maven test phase.

## demo-boolean-parameterized-pipeline
It's a simple pipeline that takes boolean parameters when we build and echo the set parameter.

## demo-string-parameterized-pipeline
It's a simple pipeline that takes string parameters when we build and echo the set parameter.

## demo-choice-parameterized-pipeline
It's a simple pipeline that gives a dropdown menu for choosing parameters while we build and echo the set parameter.

## challenge 2
A pipeline that together contains 3 different parameters (boolean, string and choice).

## demo-pipeline-with-variables
A demo pipeline that is for testing the variables functionality. Includes String, Boolean and Number variable

## demo-environment-variable-pipeline
It echos the Build Number when successful. Makes use of `BUILD_NUMBER` env variable.
