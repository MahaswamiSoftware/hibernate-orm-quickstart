###In JVM mode it doesn't throw any runtime exception. For running in JVM mode, run:

> ./mvnw install
>
> java -jar target/quarkus-jsonb-starter-1.0-SNAPSHOT-runner.jar
>
>Here it is allowing to have jsonb column in our model(known_fruits).

### Run Quarkus as a native application
 
> ./mvnw install -Dnative
>
> ./target/quarkus-jsonb-starter-1.0-SNAPSHOT-runner
>
> Here we are getting runtime exception mentioned in the description.