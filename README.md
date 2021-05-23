#Test project for the first module

Build with Gradle using following command:
gradle clean webPackage adminPackage

Build with Maven with cmd command:
mvn clean build -pl web,admin

Test with Maven with cmd command:
mvn clean test -pl web,admin