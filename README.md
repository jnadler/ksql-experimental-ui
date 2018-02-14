

# ![KSQL rocket](ksq-lrocket.png) KSQL Experimental UI


This project is an experimental UI for [KSQL](https://github.com/confluentinc/ksql).  The goal is to provide a simple visual wrapper for KSQL’s CLI.  The experimental UI is meant to be used for local development, testing and demoing KSQL. 
 
 >If you want to use KSQL in production environments, we recommend the use of KSQL’s CLI.


The KSQL Experimental UI release artifact is pulled from github/release into KSQL as part of the packaging process.

The webapp resources are bundled into the ksql-rest-app.jar as part of the ksql/rest packaging process. It is served as KSQL-REST endpoint resources.

To enable/disable the UI edit ```ksql/config/ksqlserver.properties : ui.enabled=true|false```

By default the REST endpoint runs on the ```ksqlserver.properties:listener port [8080]```
