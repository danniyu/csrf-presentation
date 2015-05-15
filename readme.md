# CSRF Presentation #

A presentation and sample app on CSRF defense and mitigation.

This is an adaptation of https://github.com/jacksingleton/csrf-presentation

## Requirements ##
- Java 7
- Maven
- Gradle
- Chrome

(Yes, this uses both Gradle and Maven right now)

## Setting up ##
- Make sure Java 7 is first on your classpath.

## Running ##

### Running the Application ###
From the piggyBank directory: `mvn spring-boot:run`

Look at the CustomerRepository class to see the fake users that get created.

### Running the Presentation ###
From the root directory `./gradlew presentation:run`
