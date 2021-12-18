First, unzip the p4.tar file.
on Lectura, type: sqlpl yanxuwu@oracle.aloe
(passwd is a8130)
then type: @oracle.sql
This step creates tables with initial data.

Then, Add the Oracle JDBC driver to your CLASSPATH environment variable:
 export CLASSPATH=/usr/lib/oracle/19.8/client64/lib/ojdbc8.jar:${CLASSPATH}

Then, compile and Run Main.java:
javac Main.java
java Main

Then the text view should pop up, we can do DMV ops according to the displaying messages.

When asking selections, type:-1 to quit the program.
