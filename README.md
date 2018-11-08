# simple-maven-archetype

This is a archetype for a clean and simple maven project.

## Getting Started

### Installing

At the moment there is no remote archetype catalog. Therefore if you want to user this archetype, you need to download/clone this project and run the following command to build the archetype.

```
mvn clean install archetype:update-local-catalog
```

After you have installed the archetype, you are able to use it.

```
mvn archetype:generate -DarchetypeGroupId=de.tebros -DarchetypeArtifactId=simple-maven-archetype -DarchetypeVersion=0.0.1 -DgroupId=de.tebros -DartifactId=my-test-project
```

Now feel free to change these files as you wish.

Finally you should correct the year and name of the LICENSE.md

```
Copyright (c) 2018 Tebros
```

### Content

The maven archetype contains the following files.

* LICENSE.md (MIT license)
* pom.xml (includes JUnit 5)
* README.md (see [here](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2))

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
