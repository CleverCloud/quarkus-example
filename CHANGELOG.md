# Changelog

## [1.1.0] - 2026-03-09

### Updated

- **Java**: 21 → 25 (LTS)
- **Quarkus**: 3.19.3 → 3.32.2
- **Maven Compiler Plugin**: 3.13.0 → 3.15.0
- **Maven Surefire Plugin**: 3.5.2 → 3.5.5
- **Maven Wrapper**: 3.3.2 → 3.3.4
- **Maven Distribution**: 3.9.9 → 3.9.13
- **Docker base images**: `ubi9/openjdk-21` → `ubi9/openjdk-25`
- **Clever Cloud env**: `CC_JAVA_VERSION` set to 25
- **README**: updated Java version references

### Removed

- Legacy `MavenWrapperDownloader.java` (no longer needed by modern Maven Wrapper)

## [1.0.0] - 2025-03-15

### Updated

- Quarkus to 3.19.3
- Java to 21
- Migrated from `quarkus-resteasy` to `quarkus-rest` (RESTEasy Reactive)
- Added Dockerfiles for JVM, native, legacy-jar, and native-micro builds
- Added Clever Cloud deployment configuration and documentation
- Rewrote README with deployment instructions

## [0.1.0] - 2019-04-12

### Added

- Initial import from [quarkus-quickstarts](https://github.com/quarkusio/quarkus-quickstarts)
- Basic REST endpoint (`/hello`)
- README
