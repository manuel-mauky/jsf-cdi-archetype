# jsf-cdi-archetype
This is a Maven Archetype to setup a simple web application
with JSF2 and CDI.

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
			-DgroupId=my.group
			-DartifactId=my.artifact'
			
Maven will ask you some questions about your project and then you are ready.

