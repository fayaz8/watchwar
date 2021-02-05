watch
=========================

This project has been generated by the Maven archetype
[camunda-archetype-ejb-war-7.2.0](http://docs.camunda.org/latest/guides/user-guide/#process-applications-maven-project-templates-archetypes).


Show me the important parts!
----------------------------

![BPMN Process](src/main/resources/process.png)


How does it work?
-----------------


How to use it?
--------------

There is no web interface to access the application.
To get started refer to the `InMemoryH2Test`.

There is also an `ArquillianTest`, which by default connects to a
Camunda BPM platform running locally on a JBoss AS 7.
You can download a Camunda BPM distribution for JBoss from the
[Camunda BPM download page](http://camunda.org/download/).

You can also use `ant` to build and deploy the example to an application server.
For that to work you need to copy the file `build.properties.example` to `build.properties`
and configure the path to your application server inside it.
Alternatively, you can also copy it to `${user.home}/.camunda/build.properties`
to have a central configuration that works with all projects generated by the
[Camunda BPM Maven Archetypes](http://docs.camunda.org/latest/guides/user-guide/#process-applications-maven-project-templates-archetypes).

Once you deployed the application you can run it using
[Camunda Tasklist](http://docs.camunda.org/latest/guides/user-guide/#tasklist)
and inspect it using
[Camunda Cockpit](http://docs.camunda.org/latest/guides/user-guide/#cockpit).


Environment Restrictions
------------------------

Built and tested against Camunda BPM version 7.2.0.


Known Limitations
-----------------


Improvements Backlog
--------------------


License
-------

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
