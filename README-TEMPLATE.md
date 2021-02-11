# {{name}} -

**v0.0.0**

### Issues

[![GitHub issues by-label](https://img.shields.io/github/issues/{{repo}}/bug)](https://github.com/{{repo}}/issues?q=is%3Aopen+is%3Aissue+label%3Abug)
[![GitHub closed issues by-label](https://img.shields.io/github/issues-closed/{{repo}}/bug)](https://github.com/{{repo}}/issues?q=is%3Aclosed+is%3Aissue+label%3Abug)

### Release

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/{{repo}}?label=latest%20stable)](https://github.com/{{repo}}/releases/latest)
![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/{{repo}}/latest)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/{{repo}}?include_prereleases&label=latest)](github.com/{{repo}}/releases)

![GitHub last commit](https://img.shields.io/github/last-commit/{{repo}})
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/{{repo}}/Java%20JUnit%20Test%20with%20Gradle)<br>

This lib provides ....

### Development <a href="https://www.conventionalcommits.org/en/v1.0.0/"><img src="https://img.shields.io/badge/conventional%20commits-✔-brightgreen"/></a>

![Lines of code](https://img.shields.io/tokei/lines/github/{{repo}})<br>

[![Code Climate issues](https://img.shields.io/codeclimate/issues/{{repo}}?label=Code%20Quality%20issues)](https://codeclimate.com/github/{{repo}})
[![Maintainability](https://img.shields.io/codeclimate/maintainability/{{repo}}.svg)](https://codeclimate.com/github/{{repo}})
[![Maintainability](https://img.shields.io/codeclimate/maintainability-percentage/{{repo}}.svg)](https://codeclimate.com/github/{{repo}})

### Usage

![Java 1.8](https://img.shields.io/badge/java-1.8-blue)
[![Maven metadata URL](https://img.shields.io/maven-metadata/v?metadataUrl=https%3A%2F%2Fniton.jfrog.io%2Fartifactory%2Fjava-libs%2Fcom%2Fniton%2F{{name}}%2Fmaven-metadata.xml)](https://niton.jfrog.io/ui/repos/tree/General/java-libs%2Fcom%2Fniton%2F{{name}})

#### Gradle

```groovy
repositories {
    maven {
        url("https://niton.jfrog.io/artifactory/java-libs/")
    }
}
```

```groovy
implementation 'com.niton:{{name}}:0.0.0'
```

#### Maven

```xml
<repositories>
  <repository>
    <id>niton</id>
    <name>niton</name>
    <url>https://niton.jfrog.io/artifactory/java-libs/</url>
  </repository>
</repositories>
```

```xml
<dependency>
  <groupId>com.niton</groupId>
  <artifactId>{{name}}</artifactId>
  <version>0.0.0</version>
</dependency>
```

### Configuration file

```json

```