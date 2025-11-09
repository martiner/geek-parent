# Geek OSS Parent POM

```xml
<parent>
    <groupId>cz.geek</groupId>
    <artifactId>geek-parent</artifactId>
    <version>X.Y.Z</version>
    <relativePath />
</parent>
```

1. [Generate token](https://central.sonatype.com/usertoken)
2. Place the token in your `~/.m2/settings.xml`:
```xml
<servers>
  <server>
    <id>central</id>
    <username>OTHlntrt</username>
    <password>your-token</password>
  </server>
```

This module is derived from [org.sonatype.oss:oss-parent:9](http://repo1.maven.org/maven2/org/sonatype/oss/oss-parent/9/oss-parent-9.pom) 
and it aims Maven projects to be released into the public [Central repository](http://central.sonatype.org/)
using [Sonatype's Open Source Software Repository Hosting (OSSRH) service](http://central.sonatype.org/pages/ossrh-guide.html).
