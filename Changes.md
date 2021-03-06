# Changes in the BigML.io Java bindings

## 1.2 version

### New Features

* Since version 1.2 we start to publish the release on the Maven Central Repository. Now, you can declare
the library dependency in your project's pom file.

    If you were using the Apache HttpClient library in your own project, now you will need to explicitly declare this
dependency in your own project's pom file, because it's not anymore a dependency of our library.

* We have removed the unnecessary dependencies with third party libraries, like Apache HttpClient and SLF4J-Log4j.

* Support for json files in UTF-8 encoding. Now we can send json objects with UTF-8 characters inside.

* Added the system property **BIGML_SEED** to allow clients to generate deterministic models.

* Add **Seed** to the tests to make them deterministic

* Contact support information has been updated

### Bugs

* Fixed bug in predictions when we were using fields in the input data that had periods in their names.

## 1.1 version

* Since version 1.1 the name of the JAR file is bigml-binding.

