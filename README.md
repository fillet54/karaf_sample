# Karaf Example

Compile and deploy to local maven repository with `mvn clean install`

To run:

```bash
feature:repo-add cxf 3.1.0
feature:repo-add mvn:com.fiftycuatro.rest/personrest-feature/1.0-SNAPSHOT/xml/features
feature:install personservice-rest
```

Navigate to `http://localhost:8181/cxf/person` and `http://localhost:8181/personrestui`.
