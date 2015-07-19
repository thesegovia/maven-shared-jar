The official release of maven-shared-jar uses a version of the Apache BCEL library
that can't deal with Java 8 files. This repository is an unmodified copy of the
official one but with the BCEL dependency updated to point to the Java 8 compatible
version that's part of the FindBugs package.

To use it locally:

    git clone https://github.com/thesegovia/maven-shared-jar
    cd maven-shared-jar
    mvn install

It will install the JAR and POM files into your ~/.m2 directory, replacing the
official ones, and your build will start using them.
