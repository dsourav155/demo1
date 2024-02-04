# SDKMAN.io

## Introduction

SDKMAN.io, short for **Software Development Kit Manager**, is a command-line tool designed to simplify the installation, management, and use of multiple SDKs across different programming languages. Originally focused on the Java ecosystem, SDKMAN.io has expanded its support to include languages such as Kotlin, Scala, Groovy, and more.

## Benefits of SDKMAN:

- Increases Productivity 
- Faster and Easier to maintain different versions.
- Changes version of your home server rather than changing the version of all others users in a global server working together. 
- Automates managing and switching between different versions. 
- You control what you own and don't disturb others on a global server.

## Installation

Launch a terminal and type in:

```
$ curl -s "https://get.sdkman.io" | bash
```

After installation, Open a new terminal and type in:

```
$ source "$HOME/.sdkman/bin/sdkman-init.sh"
```

Lastly, you can run the following to confirm the installation:

```
$ sdk version
```

## Using SDKMAN

SDKMAN will allow you to install a lot of different programs.

**Listing all options to install**

```
$ sdk ls
```

**Installing Java**

```
$ sdk install java
```

**Find a specific version:**

```
$ sdk ls java
```

**Install a specific version based on identifier from list:**

```
$ sdk install java 11.0.12-open
```

**Using a specific version:**

```
$ sdk use java 11.0.12-open
```

**Default a specific version:**

```
$ sdk default java 11.0.12-open
```

**To update SDKMAN:**

```
$ sdk update
```

**NOTE** All of the above commands will work for the other programs available such as:

- gradle
- maven
- groovy
- kotlin
- spark
- springboot

## Getting help

```
$ sdk help
```

## Conclusion

In a nutshell, SDKMAN.io is a game-changer for developers. It makes handling different programming languages a breeze, saves time, and ensures a smooth experience across various operating systems. Whether you're a seasoned pro or a beginner, incorporating SDKMAN.io into your toolbox can make your development journey much simpler. So, dive in, explore SDKMAN.io, and enjoy a hassle-free way to manage your software development kits!
