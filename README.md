## Overview ##
The common-maven-parent parent pom provides the common pieces the other Black Duck Software OSS maven projects can reuse.

In order to use this parent pom in your project you will need to include the following in your child pom:
```
  <parent>
    <groupId>com.blackducksoftware.integration</groupId>
    <artifactId>common-maven-parent</artifactId>
    <version>1.0.6</version>
    <relativePath>../common-maven-parent</relativePath>
  </parent>
```

(the relative path is optional)

The artifact is available on Maven Central here: [http://repo1.maven.org/maven2/com/blackducksoftware/integration/common-maven-parent/]


## License ##
Apache License 2.0
