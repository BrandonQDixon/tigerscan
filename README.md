# TigerScan - Email Security Scanner
*Software Engineering Project - Rowan University*

## Instructions
### Users
coming soon..

### Administrators
Managers of the TigerScan system may display the recorded activity log and access the database settings window. Upon first launching the program, a default administrator is provided, but a new one will need to be specified and created by a manager. The default administrator credentials are as follows:
```
Usermame: admin
Password: tiger2admin1676
```
Once the new administrator is created and saved to the system, the default administrator credentials are no longer valid and the new administrator is required to access management features.


## Requirements
### Maven
TigerScan can be fully built outside of an IDE by utilizing [Maven](http://maven.apache.org/) for project build management. With Maven installed, navigate to the project's root directory and run the following command:
```
mvn clean package
```
That's it! Maven will build two versions of TigerScan and output them into the "target" directory. The first .jar file will omit dependencies, while the second will include them so the program can be executed properly.


### Java
TigerScan is a Java application, which allows it to be used cross-platform. It will operate on Windows, OSX, and Linux distributions. Download Java for your specific machine on Oracle's [official Java page](https://www.java.com).


### Dependencies
These dependencies are required to properly compile the source code. If you do not wish to download them automatically using Maven, you may acquire them individually and include them with your own compilation of the source code.
- [SQLite JDBC Driver](https://github.com/xerial/sqlite-jdbc) - JDBC library for interfacing with SQLite database files in Java. Download the latest compiled version from the [download page](https://bitbucket.org/xerial/sqlite-jdbc/downloads). Currently required dependencies are as follows:
 - `sqlite-jdbc-3.14.2.1.jar`
- [Apache Lucene](http://lucene.apache.org/) - Open-source project featuring advanced text searching, indexing, analysis, spell-checking and more. Downloads can be found at the [Apache archives](http://archive.apache.org/dist/lucene/java/). Currently required dependencies are as follows:
 - `core/lucene-core-6.2.1.jar`
 - `queryparser/lucene-queryparser-6.2.1.jar`
 - `analysis/common/lucene-analyzers-common-6.2.1.jar`

**Fully compiled versions of TigerScan can be found on the [releases](https://github.com/nickschillaci1/SWENG_EmailSecurityScanner/releases) page.**
