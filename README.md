# EPAS Enablement Training

## About
EPAS Enablement Training focuses on the Enablement of Field Consultants to be able to deliver OpenShift Enterprise Engagements. Its focus is to technically deep dive into an OpenShift Enterprise.

The following list represents the key components we want to cover in this 5-day training.

- Installation of OpenShift Enterprise
  - Installation of all components from scratch (Using the Delivery Guide of OSE Core Install)
  - Explaining and Discussing Architectural Decisions within the product
    - DNS Working Setting it up from scratch and preparing it for use with OpenShift Enterprise
    - MongoDB (Accessing and Querying)
    - ActiveMQ What is its role
    - MCollective what is its role
- General OpenShift use cases
- Integration of OpenShift Enterprise into Developer workflow
- Integration of OpenShift Enterprise to streamline multi stage development
- Extending OpenShift Enterprise

## Training Outline

### Introduction into OpenShift

* Storyline
  * Customer has an ApplicationSet with Services they provide
  * they develop it and they deploy it
  * development is different than prod
  * having trouble to test efficiently
  * need to align dev and prod environments
  * need to provide developers with resources to develop on
     * trouble developers use windows laptop
     * deploy to dev machines
        * different patchlevel
        * applevel etc.
     * dev machines take weeks to deploy
     * different number of RVCS System/Control Structures
* Rapid Application Infrastructure Deployment 
  * Overview Section
  * Lab Section
     * Create an Application
     * Modify an Application with a marker file
     * create a cron job for an application
     * add an add-on cartridge
* Aligning Development/Staging and Production Environments
* Production and Capacity Benefits
  * Lab Section
     * Create a scaling Application 
        * demo application needed (load generator)
        * matt hicks has created one
          * https://github.com/matthicksj/scaling-demo
     * Look at the runtime statistics
     * Investigate Infrastructure
     * Look at the scaling algorithms
     * Demonstrate HA-Proxy SPOF
        * Discussion around SPOF
        * Workarounds
        * Existing Workarounds
* Custom Cartridge Creation
  * possible CF2 Cartridge
  * Glassfish Example (just a Proof-of-Concept though)
* Integration of external Systems
  * External Database
  * Global Variables
  * External Messaging System
  * External Webservice (maybe amazon store ui, or google, or weather.com)
  * External Logging System
  * External vs. Internal Jenkins Integration
* Monitoring
  * Nagios Integration
  * Zabbix Integration
  * SELinux Issues
  * Custom Policy
* Infrastructure / Architecture
  * Loopback Addresses
  * Multi Tenancy
  * Shared Storage
  * SSL and Encryption
  * Maven and Jenkins Integration
  * Jenkins Build and Deployment Pipeline
  * Divide Broker up into its components
     * DNS
     * ActiveMQ
     * MongoDB
* Do you need Backup?
  * Desaster Recovery
  * Fault Tolerant Storage
