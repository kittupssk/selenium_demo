# selenium_demo
Automated Tests driven by Cucumber Feature files
This is an Automated Tests repository to help automate Sanity and Regression Test Suites for apps. This build uses the following:

Selenium Web Driver
Java
Maven
Cucumber 2.4
Implements Selenium PageObjectModel
Git (source code control)


Prerequisites:
java version 8 installed
maven 3 installed
eclipse or intellij as IDE is recommended

Run/Debug your runner test file as JUnit.
Running tests on Jenkins:
Maven Command

-Denv=env_file_name -Dcucumber.options="--tags @high" clean test
