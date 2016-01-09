# CookieCutter-FRC
Cookiecutter project for FRC robot projects with Ivy. Some 4761-specific stuff is hardcoded into the project but if you fork it for your own team it should be pretty easy to customize.

## Fancy Features
* Dependency management with [Apache Ivy](https://ant.apache.org/ivy/).
* Easy [Travis CI](https://travis-ci.org/) integration out-of-the-box.
* Set up for unit testing with [JUnit](http://junit.org/) and [Mockito](http://mockito.org/) out-of-the-box.
* Support for Team 4761's [ButtonManager](https://github.com/Team4761/ButtonManager) and [DistanceSensorLib](https://github.com/Team4761/DistanceSensorLib) built in.
* .gitignore file based of the one from the [Open-RIO project](https://github.com/Open-RIO/.gitignore).
* "Clean" task for the Ant build file for quickly and easily removing binaries.

## Getting set up
1. **Clone the project.** Use [roboclone](http://simon-andrews.github.io/roboclone/).
2. **Remove the origin.** You can do this with the command `git remote rm origin`.
3. **Add the origin for your project.** You can do this with the command `git remote add origin <ORIGIN_URL>`.
4. **Refactor the package name to change it to your desired package name.**
5. **Edit ivy.xml to reflect the refactor.** Change the info element to whatever your new package name is.
6. **Add a README file.** Please.
