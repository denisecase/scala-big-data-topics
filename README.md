# scala-big-data-topics

>Manage a list of big data topics using Scala, Akka, and Akka-HTTP

## Links

- [Service]()
- [Repo](https://github.com/denisecase/scala-big-data-topics)

## Prerequisities

- OpenJDK (8 or higher)
- sbt (current)
- (Optional, if Windows) Chocolatey package manager

```PowerShell
choco install openjdk -y
choco install sbt -y
choco upgrade sbt -y
choco list --local
refreshenv
sbt --version
sbt scalaVersion
```

## Creating From Scratch

### Initialize a new repo

1. In GitHub, add a new repo
2. Add a default README.md
3. (Optional) Add License
4. Add a .gitignore using Scala template
5. Clone down to your machine

### Create standard Scala project

1. Add build.sbt
2. Add project\build.properties
3. Add project\plugins.sbt
4. Add src\main\scala\Main.scala
5. Add src\test\scala\MainSpec.scala
6. Add src\main\resources\application.conf
7. Add src\main\resources\logback.xml
8. Add src\test\resources\application-test.conf

Add VS Code extesions:

 - Scala Syntax (official)
 - Scala (sbt) by LightBend

## Add dependencies and static analysis

1. Add dependencies to build.sbt
2. Add sbt.version to project/build.properties
3. In project/plugins.sbt add Scalastyle
4. Open PowerShell as Admin and run `sbt scalastyleGenerateConfig` to create config file
5. Edit scalastyle-config.xml as desired (e.g. file header)

## Create the first route in Main.scala

1. Complete src/main/scala/Main.scala
2. Open PowerShell as Admin and run `sbt scalastyle`
3. Run `sbt run`

## Create the first test in MainSpec.scala

1. Complete src/test/scala/MainSpec.scala
2. Open PowerShell as Admin and run `sbt scalastyle`
3. Run run `sbt test`

## Resources

1. [sbt](https://www.scala-sbt.org/index.html)
2. [Akka](https://akka.io/)
3. [Akka docs](https://akka.io/docs/)
4. [akkahttp-quickstart](https://github.com/Codemunity/akkahttp-quickstart)
5. [ScalaTest](https://www.scalatest.org/at_a_glance/WordSpec)
6. [Scala on Command Line](https://docs.scala-lang.org/getting-started/sbt-track/getting-started-with-scala-and-sbt-on-the-command-line.html)
7. [Akka HTTP Quickstart](https://doc.akka.io/docs/akka-http/current/introduction.html#)
8. [Scalastyle](http://www.scalastyle.org/)
9. [Logging](https://doc.akka.io/docs/akka/2.6/typed/logging.html#logback)
10. [StackOverflow - multiple routes](https://stackoverflow.com/questions/34514372/akka-http-with-multiple-route-configurations)
11. [Scastie formatter](https://scastie.scala-lang.org/)









