# simple-maven-archetype

This is a archetype for a clean and simple maven project.

## Getting Started

### Installing

#### Remote

If it has not happened already, add the remote archetype catalog with the following URL to your IDE.

```
http://repo1.maven.org/maven2/archetype-catalog.xml
```

Now you can search for "simple-maven-archetype" in the catalog and select the latest version.

#### Local

You could also download/clone this project and run the following command to build the archetype locally.

```
mvn clean install archetype:update-local-catalog
```

After you have installed the archetype, you are able to use it.

```
mvn archetype:generate -DarchetypeGroupId=de.tebros -DarchetypeArtifactId=simple-maven-archetype -DarchetypeVersion=0.0.1 -DgroupId=de.tebros -DartifactId=my-test-project
```

#### Post-Installing 

Now feel free to change these files as you wish.

Finally you should correct the year and name of the LICENSE.md

```
Copyright (c) 2018 Tebros
```

### Content

The maven archetype contains the following files.

* .gitignore
* LICENSE.md (MIT license)
* pom.xml (includes JUnit 5)
* README.md (see [here](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2))
* src/main/java/App.java
* src/main/resources/log4j2.xml
* src/test/java/AppTest.java

JUnit 5 and Log4j are listed in the dependencies tag of the pom.xml file.

### Changing the license

By default this archetype uses a MIT license. If you want to change your license, please notice the <licenses> tag in the pom.xml file.

```
<licenses>...</licenses>
```

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/Tebros/maven-archetype-simple-project/tags). 

## Authors

* [Tebros](https://github.com/Tebros)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
