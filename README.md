# Hello OpenCL World
Maintain by Avatar Ng (http://www.minfaatong.tk), originally fork from Jeff Heaton's project repositories.

## Changes
Updated to Gradle 4.7, Java 1.8, Lwjgl 2.9.3
Added Junit 4, Log4j support

## Summary
This is my Hello World application for OpenCL, using the LWJGL framework to handle the native calls.
It is actually more of a "Hello Solar System" as it does a few things.  First, it polls all platforms
and devices and lists basic stats about your system.  Second, it performs a vector addition.  The kernel
is loaded from a resource file, rather than the usual hard-coding you see in many examples.  This project
uses Gradle.  See the README for instructions on how to run this.

This example makes use of Gradle.  It is not necessary to have Gradle installed, just use the wrapper.
To use the wrapper just use the "gradlew" command.

## Steps

To run this application simply issue the command:

`gradlew run`

## References
- Credit Jeff Heaton

