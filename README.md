# Gradle tutorial

## Installation
* Debian has old version
* Installed binary in Dev
    * not necessary to use wrapper
* Updating wrapper 

`./gradlew wrapper --gradle-version=6.4.1 --distribution-type=bin`

* [Command line completion](https://github.com/gradle/gradle-completion)

## Creating New Gradle Builds

### `init`-ed project has
* two build scripts
* wrapper
    * with config
* build.gradle - build script a.k.a. _build file_
    * tasks go here
* settings.gradle - script for configuring the above?

## Building Java Applications

## Generals

`Project` includes a collection of `Task`s

`Task` performs basic operation 

Gradle comes with library of `Task`s

Gradle includes `Plugin`s

`Plugin`s provide definitions of `Task`s

> `base` plugin defines `clean` and `build` tasks

> `Task` of type `zip` is configured by settings. Only archive file name specified, archive destination  taken from settings.

> `./gradlww properties` shows properties. How to use them in scripts? What good are they for?

### Tasks

* Copy
* Zip

### Plugins

* base

### [Command line interface](https://docs.gradle.org/4.10.3/userguide/command_line_interface.html)

`./gradlew tasks` - shows available tasks

### Build scans

> Add --scan to any command, generates a link, requires e-mail confirmation every time?
