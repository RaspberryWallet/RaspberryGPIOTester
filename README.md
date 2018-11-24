<img src="docs/logo.png" width="200" align="right">

# RaspberryGPIOTester :traffic_light:

Console application for testing state of GPIO Pins on Raspberry platform using Pi4J library.

## Requirements
- Maven
- Java 8

## Installation
```bash
# download repo
git clone https://github.com/RaspberryWallet/RaspberryGPIOTester.git
cd RaspberryGPIOTester

# build jar
mvn clean package

# copy jar to Raspberry
scp target/gpiotester-1.0-jar-with-dependencies.jar dietpi@dietpi:/tmp/gpiotester.jar
```

## Starting tester
```bash
# connect to Raspberry
ssh dietpi@dietpi

cd /tmp
java -jar gpiotester.jar
```

## Authors

We are not authors of this code. It was originally implemented by Pi4J Team as example here:
[https://github.com/Pi4J/pi4j/blob/master/pi4j-example/src/main/java/GpioListenAllExample.java](https://github.com/Pi4J/pi4j/blob/master/pi4j-example/src/main/java/GpioListenAllExample.java)

## Changelog

[//]: https://www.tablesgenerator.com/markdown_tables

| Version | Is backward- compatible | Changes       | Commit ID                                |
|---------|-------------------------|---------------|------------------------------------------|
| 1.0     | Yes                     | First release | 4dfb3c879196a20b72faa43b637ffbeb16f5f94c |
|         |                         |               |                                          |
