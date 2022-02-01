# kotlin-cli-maven-spring-surefire-pmd-cucumber-mockito-testng-hello-world

## Description
A POC for spring app using testng, cucumber, mockito,
and pmd framework with surefire plugin.

PMD analyze source code for potential bugs.

This is a simple and trivial way to start:
  - kotlin
    - springframework
    - cucumber test runner for testng
  - cucumber
    - parameterized scenario
  - mockito
    - integration of testng
    - injection

## Tech stack
- kotlin
- maven
	- mockito
  - spring
  - testng
  - cucumber
  - surefire
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
