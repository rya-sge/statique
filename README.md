# Statique

Statique is a brand new static site generator.

Build and unzip the project:

```
mvn clean install \
    && rm -fr statique \
    && unzip target/statique.zip
```

Add the bin directory to your path:

```
export PATH=$PATH:`pwd`/statique/bin
```

Executing `statique` should now produce the following result:

```
statique
Usage: statique [COMMAND]
A brand new static site generator.
Commands:
  init   Initialize a static site directory
  clean  Clean a static site
  build  Build a static site
  serve  Serve a static site
```