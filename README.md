## Orchid ##

Orchid is a Tor client implementation and library written in pure Java. 

Copyright (c) 2009-2011, Bruce Leidl
All rights reserved.

[Orchid Homepage](http://www.subgraph.com/orchid.html "http://www.subgraph.com/orchid.html")

### Maven ###

[rarguello](https://github.com/rarguello) ported the project to maven, unfortunatly his pull request wasn't merged yet

### Maven Repo ###

Since i want to play arround with it a bit, i forked rarguellos fork and deployed a maven repo on my fork. 

(many thanks to emmby for i nice stack overflow tutorial how to do this, see [http://stackoverflow.com/questions/14013644/hosting-a-maven-repository-on-github](http://stackoverflow.com/questions/14013644/hosting-a-maven-repository-on-github))

Include Orchid in your Maven project by adding following to the `pom.xml` 

```xml
    <repositories>
      <repository>
        <id>orchid-mvn-repo</id>
        <url>https://raw.github.com/jethroo/orchid/mvn-repo/</url>
      </repository>
    </repositories>

    <dependencies>
		<dependency>
			<groupId>com.subgraph.orchid</groupId>
			<artifactId>orchid</artifactId>
			<version>1.0.0</version>
		</dependency>
    </dependencies>
 ```
