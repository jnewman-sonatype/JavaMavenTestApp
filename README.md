# JavaMavenTestApp
A minimal Java application that deliberately references Maven dependencies with known vulnerabilities.
Includes build piplines for common CI/CD platforms that build the app using Maven and then perform an evaluation using Sonatype Lifecycle.

Components listed in pom.xml
- junit:junit:3.8.1 (scope:test)
- log4j:log4j:1.2.17
- commons-fileupload:commons-fileupload:1.2.2
- commons-io:commons-io:1.3.2
- com.fasterxml.jackson.core:jackson-core:2.0.4
- com.fasterxml.jackson.core:jackson-databind:2.0.4
- taglibs:standard:1.1.2
