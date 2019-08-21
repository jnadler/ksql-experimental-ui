

# ![KSQL rocket](ksq-lrocket.png) KSQL Experimental UI


This project is an experimental UI for [KSQL](https://github.com/confluentinc/ksql).  The goal is to provide a simple visual wrapper for KSQL’s CLI.  The experimental UI is meant to be used for local development, testing and demoing KSQL. 

**Note:** The latest releases of KSQL no longer support serving the UI files.   However, it's still possible to use it by running your own webserver and proxy to send the API requests to the KSQL install.   I did it with `nginx`; it wasn't too hard.   Maybe I'll commit changes to this repo one day to provide a full running environment.
 
