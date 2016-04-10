# CookieCutter-FRC
Cookiecutter project for Command-Based Java FRC robot projects with Ivy.

## Fancy Features
* Dependency management with [Apache Ivy](https://ant.apache.org/ivy/).
* Easy [Travis CI](https://travis-ci.org/) integration out-of-the-box.
* ~~Set up for unit testing with [JUnit](http://junit.org/) and [Mockito](http://mockito.org/) out-of-the-box.~~
* Support for Team 4761's [ButtonManager](https://github.com/Team4761/ButtonManager) and [DistanceSensorLib](https://github.com/Team4761/DistanceSensorLib) built in.
* .gitignore file based of the one from the [Open-RIO project](https://github.com/Open-RIO/.gitignore).
* "Clean" task for the Ant build file for quickly and easily removing binaries.

## Generating a project
1. Install [Python](https://www.python.org/downloads/)
2. Install [Cookiecutter](https://cookiecutter.readthedocs.org/en/latest/installation.html)
3. Run `cookiecutter gh:Team4761/Cookiecutter-FRC`
4. Answer the prompts that appear on your screen

## Using generated projects
1. Make sure you have Ant in your system path
2. Install [Apache Ivy](https://ant.apache.org/ivy/history/latest-milestone/install.html). Make sure to use the instructions in the "Manually" section.
3. Compile with `ant jar`.
