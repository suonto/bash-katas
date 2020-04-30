# Bash Katas
Welcome to bash katas. Bash is the most common language for Linux shell scripts. These exercises assume no previous knowledge of linux or shell scripting but you'll get to meaningful scripting in no time.

To make our work meaningful we will begin with an artificial "real world" problem.

## Scenario 1: Jenkins Disk is Full

[Jenkins](https://www.jenkins.io/) is a continuous integration engine that runs jobs. One job is like a task that can be run over and over again. Each run is called a build and its data is stored in a numbered build directory. That's all you need to know about Jenkins.

### Mission 1
Our Jenkins disk has became full of old builds. Our end users must be abusing the system. In other words, they're running a lot of builds for their jobs but never discarding old build directories. We asked our users but nobody admits that they would store more than 10 old builds per job. Can you help our Jenkins administrator identify which job(s) is(are) polluting the file system with old builds?
