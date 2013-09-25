repo
====

Maven repository for some softwares

## Repository setting for your pom.
```
  <repositories>
    <repository>
      <id>takawitter</id>
      <url>https://raw.github.com/takawitter/repo/mvn-repo</url>
      <snapshots>
        <enabled>true</enabled>
        <updatePolicy>always</updatePolicy>
      </snapshots>
    </repository>
  </repositories>
```

## Trie4j example
```
  <dependencies>
  	<dependency>
  		<groupId>org.trie4j</groupId>
  		<artifactId>trie4j</artifactId>
  		<version>0.5.0-SNAPSHOT</version>
  	</dependency>
  </dependencies>
```

## JSONMAN example
```
  <dependencies>
  	<dependency>
  		<groupId>org.jsonman</groupId>
  		<artifactId>jsonman</artifactId>
  		<version>0.0.1-SNAPSHOT</version>
  	</dependency>
  </dependencies>
```
