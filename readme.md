## CICS Transaction Gateway Liberty JCA ECI sample code

### Pre-reqs
* CICS Transaction Gateway v8.1 or later
* WebSphere Liberty 8.5.5 FP3 or later with the jca-1.6 feature installed or
* CICS TS V5.3 with Liberty and the cicsts:jcaLocalEci-1.0 feature
* Eclipse with WebSphere Development Tools installed

### Configuration
The supplied `server.xml` file shows the required configuration paramters for adding the ECI resource adapter, 
creating a connection factory and adding the classes supplied with the resource adapter to the classpath of the application. 
This file can be used as-is or the configuration options can be copied into an existing server configuration.

### Compiling the sample
The sample servlet code can be added to a Web Project. To correct any compilation errors either the cicsjee.jar 
should be added to the build path if using the CICS TG, or the CICS Liberty JVM server libraries added using the Add Library
menu if using the CICS Explorer SDK for Servlet and JSP support.


### Reference
More information about working with CICS TG resource adapters in WebSphere Liberty can be found in this [blog post] (https://developer.ibm.com/cics/2014/05/06/using-jca-with-the-cics-tg-in-websphere-liberty-profile/).
Information on porting JCA ECI applications into CICS using the JCA local ECI resource adapter in Liberty can be found in this CICS developer center [blog post] (https://developer.ibm.com/cics/2015/07/23/porting-jca-eci-applications-into-a-cics-liberty-jvm-server/)


