flatten-maven-plugin-overrides-site-xml
=======================================

Sample project for http://jira.codehaus.org/browse/MOJO-2030.

Without flatten-maven-plugin
----------------------------
* Invoke `mvn clean verify site`.
* Open `target/site/index.html`.
* The site is rendered with the `maven-fluido-skin`.

With flatten-maven-plugin
-------------------------
* Invoke `mvn -P with-flatten-maven-plugin clean verify site`.
* Open `target/site/index.html`.
* The site is rendered *erroneously* with the `maven-default-skin`.