## Overview ##
The common-maven-parent parent pom provides the common pieces the other Black Duck Software OSS maven projects can reuse.

In order to use this parent pom in your project you will need to include the following in your child pom:
```
  <parent>
    <groupId>com.blackducksoftware.integration</groupId>
    <artifactId>common-maven-parent</artifactId>
    <version>0.0.1-SNAPSHOT</version>
    <relativePath>../common-maven-parent</relativePath>
  </parent>
```

(the relative path is optional)

You will also need to specify the Black Duck Software public repository so you can download the artifact.


## License ##
Apache License 2.0
