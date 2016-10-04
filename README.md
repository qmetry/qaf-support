# qaf-support
Support project that provides ready to use steps for web and webservices

**IVY

Create or update ivysettings.xml file to add new repository. Alternately you can add settings block into ivy.xml as well.

***IVY settings

```xml
<?xml version="1.0" encoding="ISO-8859-1"?>
<ivysettings>
    <settings defaultResolver="qaf"/>
    <resolvers>
        <chain name="qaf">
            <ibiblio name="central" m2compatible="true"/>
            <ibiblio name="QAF" m2compatible="true" root="https://qmetry.github.io/qaf/dist" />
        </chain>
    </resolvers>
</ivysettings>
```
***IVY Dependency Entry

```xml
<dependency org="com.qmetry" name="qaf" rev="2.1.8" />
<dependency org="com.qmetry" name="qaf-support" rev="2.1.8" />
```


**Maven**

***Repository entry:

<repository>
    <id>qaf</id>
    <url>https://qmetry.github.io/qaf/dist</url>
</repository>

***Maven Dependency Entry:

``` xml
<dependency>
    <groupId>com.qmetry</groupId>
    <artifactId>qaf</artifactId>
    <version>2.1.8</version>
</dependency>
<dependency>
    <groupId>com.qmetry</groupId>
    <artifactId>qaf-support</artifactId>
    <version>2.1.8</version>
</dependency>
```
