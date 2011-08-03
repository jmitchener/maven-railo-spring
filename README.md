# Getting Started

## Installing railo in to local maven repository

Due to the fact that there is no public maven repository containing an
up-to-date version of Railo you must install it yourself. This can be done by
downloading the latest WAR package and running `mvn install:install-file` as
demonstrated below.

    mvn install:install-file \
            -Dfile=railo-3.2.3.000.war \
            -DgroupId=org.getrailo \
            -DartifactId=railo \
            -Dpackaging=war \
            -Dversion=3.2.3.000 \
            -DgeneratePom=true \