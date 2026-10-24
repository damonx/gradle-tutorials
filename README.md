# Gradle Tutorials

A minimal Java application built with Gradle as a learning playground for Gradle basics and JVM project setup.

This project was generated with the Gradle `init` task and includes a simple application module, a JUnit test, and the Gradle wrapper so it can be built on any machine with the required JDK installed.

## Project overview

The repository contains a single application module:

- `app/` - the main Java project
- `app/src/main/java/org/example/App.java` - entry point for the application
- `app/src/test/java/org/example/AppTest.java` - sample JUnit test
- `settings.gradle.kts` - Gradle multi-project configuration
- `gradle/libs.versions.toml` - dependency version catalog
- `gradlew` / `gradlew.bat` - Gradle wrapper scripts

## Prerequisites

- JDK 25 (the project is configured with `JavaLanguageVersion.of(25)` in the app build file)
- A Unix-like shell or PowerShell to run the Gradle wrapper

## Getting started

From the repository root, run:

```bash
./gradlew test
./gradlew run
```

The application prints:

```text
Hello World!
```

## Common Gradle commands

```bash
./gradlew clean build
./gradlew test
./gradlew run
./gradlew tasks --all
```

## Dependencies

This sample project uses:

- Guava for an example library dependency
- JUnit Jupiter for test execution

## Notes

This repository is intentionally small and acts as a starting point for experimentation with Gradle modules, Java toolchains, dependency management, and app packaging.
