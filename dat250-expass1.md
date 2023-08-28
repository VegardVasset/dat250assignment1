# Technical report

technical problems that you encountered during installation of the software development environment and how you have solved them
how you have validated (checked) that the software development environment is working
technical problems and how you (tried to) solve them,
any pending issues with this assignment which you did not manage to solve.

## Objective: 

The obejctive of this was to setup the infrastructere to build and 
package professional software systems 

## Software installed: 
- Installed Java version version 17
- Downloaded an IDE, I use IntelliJ
- Installed Gradle which is a build tool for Java
- Installed a git client and created a github account
- Installed Podman and Docker for containerization

To verify that all these worked I ran the following commands in the terminal and checked that 
they corresponded with what was stated in the setup guide
- `java --version`
- `gradle --version`
- `git --version`
- `podman --version`
- `docker --version`

## Things done: 
- Created a github repository and cloned it to my local machine
- Sat up a build system with gradle and verifyed that it worked by running the command `gradlew build` `gradlew run` and `gradlew check`
- Changed app.java with the provided code and added dependency for Javalin in the build.gradle file and ran the command `gradlew run` to verify that it worked
- Splitted up the convertion logic into its own method and added some tests for it, and ran the command `gradlew check` to verify that it worked
- Added a dockerfile in order to containerize the application. 
- Built the image using podman and pushed the image to the dockerhub repository I created. 

## Technical problems:
I did not encounter any specific technical problems during this assignment. All the commands and installments worked quite well. 
The only thing I did differently was to use brew instead of sdkman to install java and gradle.


## DockerHub URL: 
https://hub.docker.com/repository/docker/vvasset/dat250/general