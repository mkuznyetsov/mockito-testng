# Mockito for TestNG

Mockito utility classes for easy integration with TestNG

## Installation

```Gradle
repositories {
  maven {
    //For now, we plan to start releasing to Maven Central soon
    url "https://dl.bintray.com/mockito/maven"
  }
}
dependencies {
  testCompile "org.mockito:mockito-testng:VERSION"
}
```

For latest version, see the [release notes](/docs/release-notes.md).

## Usage

See the test source code for examples.

Can you contribute usage information for this section of README file?
Please send us a pull request!

## Developing

- open in IDEA to develop or run ```./gradlew idea``` and then open in IDEA
- ```./gradlew build``` - tests code and assembles artifacts
- ```./gradlew publishToMavenLocal``` - publishes to local Maven repo, useful for local testing

## History

The original TestNGListener was a part of the core Mockito repository. However, the jar was never released. Core Mockito team does not work with TestNG so it was hard for us to maintain TestNG integration. In Summer 2018 we moved the TestNG integration to a separate repository under "Mockito" organization on GitHub.

## Help

We are looking for maintainers of TestNG integration. Let us know if you want to join! Mockito core team has limited capacity and focuses on the core library.