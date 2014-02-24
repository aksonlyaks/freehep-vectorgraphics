---
layout: default
title: FreeHEP - Vector Graphics
lead: Building
slug: user
dir: .
---
You need java, maven (mvn) and git installed to be able to build the vectorgraphics library. 

```
git clone git@github.com:freehep/freehep-vectorgraphics.git
cd freehep-vectorgraphics
mvn clean install
``` 

To run the example:

```
java -jar freehep-graphics2d-export-example/target/freehep-graphics2d-export-example-2.3.jar
```