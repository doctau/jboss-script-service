jboss-script-service
====================

Do you remember bsh deployer service? Now we are JSR-223, javax.script!

Usage
-----

Deploy target/script-service.jar to $JBOSS_HOME/standalone/deployments directory and boot JBoss AS.

You'll see $JBOSS_HOME/standalone/scripts directory created and you can deploy any scripts to this directory.

Example
-------

helloworld.js:

    java.lang.System.out.println("Hello world!")

TODO
----

* Document how to add other languages support
* Fix module dependency issue when adding other script languages
* Allow "service" style scripts that support lifecycle methods and expose as JMX MBean
