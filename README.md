# quarkus-spring-api

This is a Spring Dependency API only dependency. The idea is to have only the classes used by Quarkus (and the transitive dependencies)
This absolutely minimum dependencies would be a great benefit to reduce the footprint of Quarkus applications using the spring modules.

## Release

To release a new version, follow these steps:

https://github.com/smallrye/smallrye/wiki/Release-Process#releasing

The staging repository is automatically closed. The sync with Maven Central should take ~30 minutes.
