# Hello World in Kotlin

A minimal Kotlin implementation of "Hello, World!".

## Installation

### macOS
```bash
brew install kotlin
```

### Linux
```bash
sudo snap install kotlin --classic  # Ubuntu/Debian
sudo dnf install kotlin  # Fedora/RHEL
```

### Windows
Download from https://kotlinlang.org/docs/command-line.html

## Running

```bash
kotlinc Main.kt -include-runtime -d hello.jar
java -jar hello.jar
```

## Code Explanation

Simple main function using println for console output.
