# H2-implementation
Changes implemented in H2 database.

This repository contains two separate files including the original H2 database and the modified version of it.

Following changes are added to the modified version:

1) Added the functionality of dropping multiple columns in a table using single query.
2) Implemented and added the 'enum' feature to H2 database.
3) Added feature to select all rows from multiple tables.


Following files are modified:

==== Files Changed ====

src/main/org/h2/command/Parser.java 
src/main/org/h2/command/Column.java 
src/main/org/h2/expression/Datatype.java
src/main/org/h2/value/Value.java
src/main/org/h2/server/web/WebApp.java
