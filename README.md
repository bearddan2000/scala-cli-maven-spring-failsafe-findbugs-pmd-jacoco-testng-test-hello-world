# scala-cli-maven-spring-failsafe-findbugs-pmd-jacoco-testng-test-hello-world

## Description
Analyze source code for potential bugs.
Analyze source code for bugs.
A POC for spring app using testng
framework with jacoco and failsafe plugins.

## Tech stack
- scala
- maven
	- findbugs
	- pmd
  - spring
  - testng
  - failsafe
  - jacoco

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
