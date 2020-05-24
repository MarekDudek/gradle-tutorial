# Gradle tutorial

## Installation
* Debian has old version
* Installed binary in Dev
    * not necessary to use wrapper
* Updating wrapper 

`./gradlew wrapper --gradle-version=6.4.1 --distribution-type=bin`

* [Command line completion](https://github.com/gradle/gradle-completion)

## Creating new Gradle builds

### Init-ed project has
* two build scripts
* wrapper
    * with config
* build.gradle - build script
    * tasks go here
* settings.gradle - script for configuring the above?

# Generals

`Project` includes a collection of `Task`s

`Task` performs basic operation 