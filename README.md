# Shikanga Developer Cheat Sheet
Useful tools, tips, commands etc.. you name it, the stuff that gets developers through the day

### Essential JVM developer tools?

* #### SDKMAN!
> SDKMAN! is a tool for managing parallel versions of multiple Software Development Kits on most Unix based systems. It provides a convenient Command Line Interface (CLI) and API for installing, switching, removing and listing Candidates.
[sdkman!](https://sdkman.io/)

* ##### How to install GraalVM with SDKMAN!
```
sdk install java 19.3.0.r8-grl
```
couldn't be simpler! :)


### Maven

* ##### Setting up the maven wrapper
> We will use the following Maven plugin for auto-installation in our project. [Takari Maven Plugin](https://github.com/takari/takari-maven-plugin)
In the main folder of the project, run this command:
```
mvn -N io.takari:maven:wrapper
```
To specify the version of Maven use:
```
mvn -N io.takari:maven:wrapper -Dmaven=3.5.2
```


### Useful Linux Commands

* ##### How to kill a process running on particular port in Linux?
```
kill -9 $(lsof -t -i:3000 -sTCP:LISTEN)
```
