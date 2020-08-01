# quarkus-vuejs-archetype
Just a basic config using Quarkus and Vue CLI

## Compile archetype
``` bash
mvn clean install
```

## Generate project
``` bash
mvn archetype:generate                                \
  -DarchetypeGroupId=io.github.gdiazs                 \
  -DarchetypeArtifactId=quarkus-vuejs-archetype       \
  -DarchetypeVersion=1.0.0-SNAPSHOT                   \
  -DgroupId=com.mycompany                             \
  -DartifactId=my-awesome-project
```

## Compile and run project in dev mode.
``` bash
cd my-awesome-project
mvn clean package exec:exec@npm-watch quarkus:dev
```
## Backend
Java backend as always in `src/main/java`, nothing new and all maven standars

## Front end
In this case `src/main/webapp` is the vue project directory, so no specific name

## Quarkus Guides
https://quarkus.io/guides/

## Vue CLI Guide
https://cli.vuejs.org/guide/

All credits to  Dmytro Chaban	(https://quarkify.net/build-run-and-deploy-vuejs-app-with-quarkus/)

