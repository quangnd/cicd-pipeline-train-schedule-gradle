# cicd-pipeline-train-schedule-gradle

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.

## Requirements

Instructions & Tasks
In this scenario, developers have created the first prototype of the train-schedule app. They need you to create a Gradle build for it. The developers need this build to execute some automated tests that they have written. If the automated tests pass, the build needs to produce a packaged archive that includes the application code and its dependencies. The archive should be located in the project folder as dist/trainSchedule.zip.

In short, this automation needs to:

- Have a build task that can be called to execute the entire build process
- Execute some automated tests (the build should fail if any of the tests fail)
- Package the code and its dependencies into a zip archive called dist/trainSchedule.zip

Prerequisites: A GitHub.com account

In order to accomplish this, you will need to:

- Configure git for ssh authentication with GitHub.com
- Create a personal fork of the sample repository https://github.com/linuxacademy/cicd-pipeline-train-schedule-gradle
- Clone your personal fork from GitHub
- Initialize the project with gradle
- Create a gradle build task
- Include the com.moowork.node plugin in the gradle project
- Execute automated tests as part of the build with the npm_test task
- Create a task to generate a zip archive (dist/trainSchedule.zip) of the files that need to be depoyed to production
- Make sure task dependencies are set up so tasks execute in the correct order
- Commit and push these changes to your GitHub fork

Some useful links:

Gradle wrapper documentation: https://docs.gradle.org/current/userguide/gradle_wrapper.html

## Running the app

It is not necessary to run this app locally in order to complete the learning activities, but if you wish to do so you will need a local installation of npm. Begin by installing the npm dependencies with:

    npm install

Then, you can run the app with:

    npm start

Once it is running, you can access it in a browser at [http://localhost:3000](http://localhost:3000)
