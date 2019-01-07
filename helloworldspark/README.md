
Build uber jar file with all the dependencies for spark-submit

This is practice following https://crunchify.com/how-to-create-build-java-project-including-all-dependencies-using-maven-maven-resources-maven-dependency-maven-jar-plugin-tutorial/

uberjar branch: 
https://crunchify.com/how-to-create-only-one-executable-jar-file-with-all-required-jars-properties-and-resources/
https://maven.apache.org/plugins/maven-shade-plugin/examples/executable-jar.html

run mvn clean install in main folder
then move to target and run java -jar sparkappmain.jar
