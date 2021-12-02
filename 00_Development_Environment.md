# Development Environment

2021.12.02

---

[TOC]

---



## Overview

- A text editor
- An NFC-enabled Android phone
- A few NFC tags
- The Android software development kit
- The Cordova CLI
- Node.js and the Node Package Manager(npm)



## 1. Setting Up the Development Environment

Android SDK

> http://bit.ly/sdkandroid

- Download Android Studio

JDK (Java Development Kit)

> http://java.oracle.com

- Download Java SE

Apache Ant

> http://bit.ly/apacheant

```
manages the build process for Android programs
```

- Download Ant ZIP file
- Extract the file to the C:\ drive

### Install the Android Platform Tools

### Install Node.js and npm

> http://nodejs.org

```
Node.js is a platform for developing network applications in JavaScript.
```

- Install Node.js
- Also install Git

### Install Cordova CLI for PhoneGap

```
Cordova pakage gives you the PhoneGap framework
```

- Open a Terminal or Command Prompt and install the Cordova package

- Run the following command in a Command Prompt window:

  ```bash
  $ npm install -g cordova
  ```

- You can now create a PhoneGap project just by typing the followings:

  ```bash
  $ cordova create project-location prackage-name app-name
  ```

  

## Creating a PhoneGap Project

- Change directories you like to keep projects in and create a folder(ex. Basic) in

- Use the `cordova create` command to create a project:

  ```
  $ cordova create Basic com.example.hello Hello
  ```

  
