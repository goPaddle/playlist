playlist project
================

Building and running on Unix
-----

1. Install Java 7 JDK or higher.  Validate it with `java -version`   It should be 1.7 or 1.8.  Validate the compiler as well with `javac -version`

2. Install Maven.

3. Build the project dependencies from the playlist directory by typing:

	mvn validate

4. To run playlist:

    mvn verify cargo:run

5. Visit the application at: `http://localhost:8080/playlist`
