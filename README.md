
# Aliyun TSDB SDK for Java

[![Build Status](https://travis-ci.com/aliyun/aliyun-tsdb-java-sdk.svg?branch=master)](https://travis-ci.com/github/aliyun/aliyun-tsdb-java-sdk)

The Aliyun TSDB SDK for Java enables Java developers to easily work with Aliyun TSDB, compatible OpenTSDB protocol. You can get started in minutes using ***Maven***. 

- [Developer Guide](https://help.aliyun.com/document_detail/61634.html)
- [Issues](https://github.com/aliyun/aliyun-tsdb-java-sdk/issues)
- [Release](https://github.com/aliyun/aliyun-tsdb-java-sdk/releases)

## Requirements

- Java 1.6 or later
- Maven

## Install

The recommended way to use the Aliyun TSDB SDK for Java in your project is to consume it from Maven. Import as follows:

```
<dependency>
    <groupId>com.aliyun</groupId>
    <artifactId>hitsdb-client</artifactId>
    <version>0.3.4</version>
</dependency>
```

See the Setup section of [the SDK Reference](https://help.aliyun.com/document_detail/61634.html) for more information about installing the SDK through other means.


## Build

Once you check out the code from GitHub, you can build it using Maven. Use the following command to build:

```
mvn clean install -DskipTests
```

