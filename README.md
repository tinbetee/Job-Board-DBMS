# A9 – Job Board Database (Oracle + Java)

This is a Java console application that connects to an Oracle database using JDBC.

## Project Structure

```text
src/      -> Java source files
lib/      -> JDBC driver (ojdbc6.jar)

THINGS TO HAVE:
- Since this uses the University Oracle DB, a connection to TMU must be established (VPN or WIFI).
- To clone this project, you must install  GIT. You may do so here: git-scm.com

-HOW TO RUN THE PROGRAM (for terminal Java program):
1. OPEN TERMINAL
2. PASTE THE FOLLOWING:
  - git clone https://github.com/musheersid098/Job-Board-DBMS
  - cd Job-Board-DBMS
  - mkdir out
  - javac -cp "lib/*" -d out src\JdbcOracleConnectionTemplate.java
  - java -cp "out;lib/*" JdbcOracleConnectionTemplate
3. USE TMU ORACLE DB USERNAME AND PASSWORD
4. FOLLOW ONSCREEN STEPS

-HOW TO RUN THE UI APP
1. OPEN TERMINAL
2. PASTE THE FOLLOWING:
  - git clone https://github.com/musheersid098/Job-Board-DBMS
  - cd Job-Board-DBMS
  - cd ui
  - start index.htmL
3. USE TMU ORABLE DB USERNAME AND PASSWORD
4. FOLLOW ONSCREEN STEPS  
