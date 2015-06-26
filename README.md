## SBT Starter template for a very basic scala project.

### Versions:

Scala: 2.11.7

sbt: 0.13.8

sbt Eclipse plugin: 4.0.0
https://github.com/typesafehub/sbteclipse

ScalaTest: 2.2.4
http://scalatest.org/

### Using:

1) Copy this and rename the root folder to your project name

2) Change the project name in build.sbt

3) Import into IDE

Eclipse:
- run "sbt eclipse" at terminal o generate project files
- import project into Eclipse

IntelliJ
- import project into IntelliJ

### File Notes:

General project settings are in build.sbt

SBT version in project/build.properties

SBT Eclipse version in project/eclipse.sbt
I keep this out of plugins.sbt since it isn't project specific and can be deleted if Eclipse won't be used

project/plugins.sbt exists but is empty
