# Modern Java Development

A comprehensive Java project showcasing modern Java development practices and patterns using Java 17+.

## Overview

This repository contains well-structured source code with complete documentation, demonstrating best practices in modern Java development including:
- Clean code principles
- Object-oriented design patterns
- Functional programming concepts
- Modern Java features (Records, Sealed Classes, Pattern Matching, etc.)

## Project Structure

```
Modern_Java_Development/
├── README.md                          # Main project documentation
├── vds_docs/                          # Additional documentation folder
└── vds_source_code/
    └── modern-java-development/       # Maven project root
        ├── pom.xml                    # Maven configuration
        ├── src/
        │   ├── main/
        │   │   ├── java/
        │   │   │   └── com/vds/modernjava/basics/  # Core application code
        │   │   └── resources/         # Configuration and resource files
        │   └── test/
        │       └── java/              # Unit tests
        └── target/                    # Build output directory
```

## Requirements

- **Java**: JDK 17 or higher
- **Maven**: 3.6.0 or higher

## Getting Started

### 1. Build the Project

```bash
cd vds_source_code/modern-java-development
mvn clean compile
```

### 2. Run Tests

```bash
mvn test
```

### 3. Package the Application

```bash
mvn clean package
```

## Project Configuration

- **Group ID**: com.vds
- **Artifact ID**: modern-java-development
- **Version**: 1.0-SNAPSHOT
- **Java Source Level**: 17
- **Java Target Level**: 17

## Key Features

- Modern Java language features and APIs
- Maven-based project management
- Comprehensive test coverage
- Clean code architecture
- Modular design patterns

## Documentation

Additional documentation can be found in:
- [vds_docs/](vds_docs/) - Detailed documentation folder

## Building and Testing

### Build from Command Line

```bash
# Full build with tests
mvn clean install

# Build without tests
mvn clean install -DskipTests

# Compile only
mvn compile
```

### Run Tests

```bash
# Run all tests
mvn test

# Run specific test class
mvn test -Dtest=ClassName

# Run with coverage
mvn test jacoco:report
```

## IDE Setup

### Eclipse/STS
1. Right-click → Configure → Convert to Maven Project (if needed)
2. Right-click → Maven → Update Project

### IntelliJ IDEA
1. Open → Select the project root folder
2. Mark `src/main/java` as Sources Root
3. Mark `src/test/java` as Tests Root

### VS Code
1. Install Extension Pack for Java
2. Open the project folder
3. Maven plugin will automatically detect pom.xml

## Contributing

When contributing to this project:
1. Follow Java coding standards
2. Write comprehensive Javadoc comments
3. Include unit tests for new features
4. Ensure all tests pass before submitting
5. Update documentation as needed

## License

This project is provided for educational and learning purposes.

## Resources

- [Java 17 Documentation](https://docs.oracle.com/en/java/javase/17/)
- [Apache Maven Documentation](https://maven.apache.org/guides/)
- [Clean Code Principles](https://en.wikipedia.org/wiki/Clean_code)

---

**Last Updated**: April 2026
