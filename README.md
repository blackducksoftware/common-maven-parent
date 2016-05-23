## Overview ##
The common-maven-parent parent pom provides the common pieces the other Black Duck Software OSS maven projects can reuse.

In order to use this parent pom in your project you will need to configure the following:
 -set the environment variable MAVEN_REPO to your local .m2 repo
 -create a symbolic link by executing 'ln -s /path/to/your/local/clone/of/common-maven-parent/settings.xml /path/to/your/local/maven/repo/settings.xml. (Ex: ln -s /Users/<username>/git-source/common-maven-parent/settings.xml /Users/<username>/.m2/settings.xml)


## License ##
Apache License 2.0
