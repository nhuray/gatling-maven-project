Gatling Maven Project
=====================

Welcome to the Gatling Maven Project

Introduction
------------

[Gatling](http://gatling-tool.org/) is an Open Source Stress Tool with:

 - High performances
 - Simple concepts
 - A DSL to describe scenarios
 - HTTP support
 - A scenario recorder
 - Meaningful reports

[Maven](http://www.springsource.org/spring-framework) is one of the most popular build automation tool in the Java world.


This project provide a simple method for integrating Gatling with Maven.


Versions
------------

The current version of the project is based on the Gatling version : **1.3.4**.

Usage
-----

Checkout the project and run the simulations with the following command :

```shell
mvn gatling:execute
```

To run a specific simulation you have to use this command :

```shell
mvn gatling:execute -Dgatling.simulation=basic.BasicExampleSimulation
```


Have fun :-)
