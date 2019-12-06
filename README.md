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

### Useful Linux Commands

* ##### How to kill a process running on particular port in Linux?
```
kill -9 $(lsof -t -i:3000 -sTCP:LISTEN)
```
