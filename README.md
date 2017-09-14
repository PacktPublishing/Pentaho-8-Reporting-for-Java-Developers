# Pentaho 8 Reporting for Java Developers
This is the code repository for [Pentaho 8 Reporting for Java Developers](https://www.packtpub.com/big-data-and-business-intelligence/pentaho-8-reporting-java-developers?utm_source=github&utm_medium=repository&utm_campaign=9781788298995), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This hands-on tutorial, filled with exercises and examples, introduces the reader to a variety of concepts within Pentaho Reporting. With screenshots that show you how reports look at design time as well as how they should look when rendered as PDF, Excel, HTML, Text, Rich-Text-File, XML, and CSV, this book also contains complete example source code that you can copy and paste into your environment to get up-and-running quickly. Updated to cover the features of Pentaho 8, this book will teach you everything you need to know to build fast, efficient reports using Pentaho. If your interest lies in the technical details of creating reports and you want to see how to solve common reporting problems with a minimum of fuss, this is the book for you.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
// Defining the connection provider.
DriverConnectionProvider provider = new DriverConnectionProvider();
provider.setDriver("org.hsqldb.jdbcDriver");
provider.setProperty("user", "pentaho_user");
provider.setProperty("password", "password");
provider.setUrl("jdbc:hsqldb:./resources/sampledata/sampledata");
```

Pentaho Reporting tools are cross-platform applications and will run in Linux, Windows, macOS, and other Java supported environments. The Reporting Engine is backwardcompatible with previous versions of JDK, but it is always recommended to use the latest one. In the case of Pentaho 8, JDK version 1.8 is suggested.
All the examples contained into this book are developed using an Ubuntu operating system v16.04 LTS with 4 GB of RAM and an Intel i7 processor. The development environment was composed by Java JVM 1.8.0_131, Apache Maven 3.3.9, Git version 2.7.4. This configuration is not mandatory for you to run the examples, but it is shared as a reference and suggestion to run the examples with success.
If you are an information technologist and don't want to cover the development tasks, Apache Maven and Git need not be installed into your laptop.

## Related Products
* [Pentaho Reporting 3.5 for Java Developers](https://www.packtpub.com/big-data-and-business-intelligence/pentaho-reporting-35-java-developers?utm_source=github&utm_medium=repository&utm_campaign=9781847193193)

* [Java EE 8 Application Development](https://www.packtpub.com/application-development/java-ee-8-application-development?utm_source=github&utm_medium=repository&utm_campaign=9781788293679)

* [Apache Spark 2.x for Java Developers](https://www.packtpub.com/big-data-and-business-intelligence/apache-spark-2x-java-developers?utm_source=github&utm_medium=repository&utm_campaign=9781787126497)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
