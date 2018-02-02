#  Introduction

This Nursa Reactome Portal fork of the GSEA repository builds a jar file
for use in Reactome.

Prepare the jar file as follows:

1. Open a console on the project directory.

2. Execute ANT:

       ant

3. Run the following:

       mvn install:install-file -Dfile=dist/gsea-reactome-<version>.jar \
           -DgroupId=edu.mit.broad -DartifactId=gsea-reactome
           -Dversion=<version> -Dpackaging=jar

   where `<version>` is the generated jar version.
 