# CloudSim Setup Guide

## Introduction
This guide provides step-by-step instructions for setting up CloudSim in the Eclipse IDE for your project. CloudSim is a framework for modeling and simulating cloud computing infrastructures and services.

### Prerequisites
- Eclipse IDE is required to use CloudSim.

## Step 1: Installation of Java
Make sure Java is installed on your system. Follow these steps:

1. Open a command prompt and check if Java is installed by running the command: `java -version`.

2. If Java is not installed, download it from [Oracle's official website](https://www.oracle.com/java/technologies/downloads/#jdk21) according to your system architecture (32-bit or 64-bit).

3. Install the Java setup.

4. Set the PATH variable for Java:
    - Copy the bin folder path from your Java installation directory (e.g., C:\Program Files\Java\jdk-19\bin).
    - Open System Properties -> Advanced -> Environment Variables.
    - In the "System variables" section, find the "Path" variable, click "Edit," and add a new entry with the copied bin path.

## Step 2: Download CloudSim and Additional JARs
1. Download CloudSim 3.0.3.zip from [CloudSim Releases](https://github.com/Cloudslab/cloudsim/releases/tag/cloudsim-3.0.3).

2. Download Apache Commons Math 3 JAR (version 3.6.1) from [Maven Repository](https://mvnrepository.com/artifact/org.apache.commons/commons-math3/3.6.1).

## Step 3: Eclipse IDE Installation
1. If you have installed a 64-bit Java, download 64-bit Eclipse; otherwise, download 32-bit Eclipse.

2. Download Eclipse IDE from [Eclipse Downloads](https://www.eclipse.org/downloads/packages/).

## Step 4: Run CloudSim in Eclipse
1. Extract the contents of the CloudSim 3.0.3.zip file.

2. Copy the commons-math-3-3.6.1.jar file into the "jar" folder of the CloudSim 3.0.3 directory.

3. Open Eclipse and create a new Java project, referencing the CloudSim 3.0.3 folder.

4. You are now ready to develop and run your CloudSim-based project in Eclipse.

## Conclusion
You have successfully set up CloudSim in the Eclipse IDE. Follow these steps to ensure a smooth development experience for your cloud computing simulation project.
