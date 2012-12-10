# jsf-cdi-archetype
This is a Maven Archetype to setup a simple web application
with JSF2 and CDI. The tomcat 7 plugin is also available.

## Included Libraries
* Apache MyFaces 2 API
* Apache MyFaces 2 Impl
* Weld Servlet
* Junit
* Mockito
* Fest-Assert 2 



## How-To
1. Checkout the project
2. `mvn install` to get the archetype in your local maven repository
3. Type in your console (in a single line):

		mvn archetype:generate
			-DarchetypeGroupId=eu.lestard
			-DarchetypeArtifactId=jsf-cdi-archetype
			-DarchetypeVersion=0.0.1
			-DgroupId=your.group.id
			-DartifactId=your.artifact.id

4. To start the tomcat server:

	1. Switch in the generated project directory
	2. build the application with `mvn install`
	3. start the tomcat server with `mvn tomcat7:run`
	4. The url is `http:\\localhost:8080\your.artifact.id`
