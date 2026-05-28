# Unified Data Migration System

## Project Overview

The Unified Data Migration System is a web-based application developed to transfer and manage data between Oracle and MySQL databases efficiently. The system automates the ETL (Extract, Transform, Load) process and provides a simple interface for database connection, table selection, and migration monitoring.

## Features

* Database migration between Oracle and MySQL
* ETL process implementation
* Dynamic table retrieval and conversion
* JDBC database connectivity
* User-friendly JSP interface
* Real-time migration handling
* Session-based authentication
* Error handling and validation

## Technologies Used

* Java
* JSP
* JDBC
* MySQL
* Oracle Database
* HTML
* CSS
* Apache Tomcat

## Project Structure

```text
datamigration/
│
├── WEB-INF/
│   └── lib/
│
├── index.jsp
├── home.jsp
├── convert.jsp
├── showTables.jsp
├── logout.jsp
```

## How to Run the Project

1. Install Apache Tomcat Server
2. Configure MySQL and Oracle databases
3. Add JDBC drivers inside `WEB-INF/lib`
4. Place the project folder inside Tomcat `webapps`
5. Start Tomcat Server
6. Open browser and run:

```text
http://localhost:8080/datamigration
```

## Future Enhancements

* Support for more databases
* Cloud database integration
* Improved UI design
* Automated backup system
* Advanced security features
