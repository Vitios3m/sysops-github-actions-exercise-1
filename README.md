# sysops-github-actions-exercise-1
A sample python webserver project in Docker which prints the hostname and IP of the container, used to demonstrate GitHub Actions.

## Exercise
The aim is to configure two GitHub actions, in the project to automate CI.

### Step 1
Fork this repository into your own account in order to be able to modify it and to be able to make new commits.

### Step 2 - Add a workflow to check the syntax of the python application
Go to the *Actions* button, search for an action named "Python application".

Configure it.

Change the configuration to run using python version "3.11" only.

Remove the "test with pytest" step since there is no testing implemented in the example project.

Finally, commit the addition of this Action.

Go again to the *Actions* button and wait to see the result of the execution of the new workflow.

*What is the result of the "Lint with flake8" step ?*


### Step 3 - Add a workflow to build a docker image of the project
Go to the *Actions* button, search for an action named "Docker image".

Configure it.

Change the configuration to generate an image with the tag "sysops-github-actions-exercise-1" instead of "my-image-name".

Then, commit the addition of this Action.

Go again to the *Actions* button and wait to see the result of the execution of the new workflow.

*What is the result of the "Build the Docker image" step (the last two lines of the output) ?*







