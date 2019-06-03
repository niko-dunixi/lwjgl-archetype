# lwjgl-archetype
## What

It is an artifact to help developers create brand new [Light Weight Java Game Library (LWJGL)](https://www.lwjgl.org/#learn-more) based projects.

## Usage

Where ever you create your projects, run the following to create a brand new LWJGL and follow the prompts to customize your project

```bash
mvn archetype:generate \
  -DarchetypeGroupId=io.paulbaker.archetypes \
  -DarchetypeArtifactId=lwjgl-archetype \
  -DarchetypeVersion=1.1
```

To make running your application simpler, the pom is configured to run whenever a jar is created.

Observe this by running `mvn package`
