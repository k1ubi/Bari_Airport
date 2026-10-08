<div align="center">
<img src="./assets/hero.svg" width="100%"/>
</div>


```
▓▒░ 0x00 // ABOUT ░▒▓
```


Airport management system built for an IT lab exam. Java web application
covering flight scheduling, gate assignment, and passenger manifests. Runs on
Tomcat with a MySQL backend.

<br>

```
▓▒░ 0x01 // STACK ░▒▓
```


| | |
|---|---|
| language | Java (Servlets / JSP) |
| database | MySQL |
| server | Apache Tomcat |
| context | Università degli Studi di Bari — IT Lab |

<br>

```
▓▒░ 0x02 // SETUP ░▒▓
```


```bash
# 1. import schema
mysql -u root -p < src/main/resources/schema.sql

# 2. configure DB connection in web.xml

# 3. build and deploy
mvn clean package
cp target/bari_airport.war $CATALINA_HOME/webapps/
```

<br>

<div align="center">

`.: . . : <[ end of transmission ]> : . :.`

</div>
