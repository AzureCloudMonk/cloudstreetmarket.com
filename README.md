# cloudstreetmarket.com

![Build Status](https://travis-ci.org/alex-bretet/cloudstreetmarket.com.svg?branch=master)
[![Gitter chat](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/alex-bretet/cloudstreetmarket.com?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
![License](https://img.shields.io/aur/license/yaourt.svg)

This project is the application developed with the book [Spring MVC Cookbook](https://www.packtpub.com/web-development/spring-mvc-cookbook)

Read more in the [WIKI](https://github.com/alex-bretet/cloudstreetmarket.com/wiki)

## Build the app

1. You must have a %JAVA_HOME% environment variable pointing to the root directory of a JDK8.
2. From the command line do:

  ```
  git clone https://github.com/alex-bretet/cloudstreetmarket.com.git
  cd cloudstreetmarket.com
  mvn clean install
  ```

## Run the app

1. Copy-paste the entire [app](https://github.com/alex-bretet/cloudstreetmarket.com/tree/master/app) directory to your ${user.home}

2. Please refer to the Wiki page [Running the app](https://github.com/alex-bretet/cloudstreetmarket.com/wiki/Running-the-app)

## IDE setup

For the usage inside an IDE do the following:

1. Make sure you have an Eclipse with m2e installed.
2. Import the checked out code through *File > Import > Existing Maven Project…*

## Project description

The project uses:

- [Spring (MVC)](http://github.com/spring-projects/spring-framework) - 4.2.1.RELEASE
- [Spring Data JPA](http://github.com/spring-projects/spring-data-jpa) - 1.8.0.RELEASE
- [Spring HATEOAS](http://github.com/spring-projects/spring-hateoas) - 0.17.0.RELEASE
- [Spring Security](http://github.com/spring-projects/spring-security) - 4.0.2.RELEASE
- [Spring Social](https://github.com/spring-projects/spring-social) - 1.1.0.RELEASE
- [Spring Session](https://github.com/spring-projects/spring-social) - 1.0.2.RELEASE

## The Book

[![spring-mvc-cookbook-img]](http://www.amazon.co.uk/Spring-MVC-Cookbook-Alex-Bretet/dp/1784396419) 

<!---
Link References
-->

[spring-mvc-cookbook-img]:http://ecx.images-amazon.com/images/I/518gBtl%2BMpL.jpg
