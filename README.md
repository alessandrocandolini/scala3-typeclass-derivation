# scala3-typeclass-derivation

## Run the tests

```shell
sbt test
```

## Build fat jar 

The project uses `sbt-assembly` to create a "fat" jar
```
sbt assembly
```

The plugin is configured explicitly to run tests on `assembly` task. The generated jar is `scala3-typeclass-derivation.jar.jar`
