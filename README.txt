Build
mvn package

Run
java -jar target/maven-repo-generator-1.0.jar <absolute path to dist artifacts file>

Output the zip file maven-repo.zip in the current directory.

Example
java -jar target/maven-repo-generator-1.0.jar wildfly/dist/target/wildfly-galleon-pack-18.0.0.Beta1-all-artifacts-list.txt 