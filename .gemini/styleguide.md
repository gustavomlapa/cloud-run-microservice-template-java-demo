# Java Style Guide

## Overview

This document outlines the coding style conventions for Java development in this project. Consistency in style improves readability and maintainability of the codebase.

## Primary Reference

We adhere to the **[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)** as the primary source for our conventions. All developers should familiarize themselves with this guide.

## Key Highlights & Conventions

While the full guide should be consulted, some key points often referenced include:

* **Formatting:**
    * Use 2 spaces for indentation (no tabs).
    * Column limit is 100 characters. Line wrapping should be applied where necessary.
    * Use K&R style ("Egyptian brackets") for braces, with no line break before the opening brace.
    * Always use braces `{}` for `if`, `else`, `for`, `do`, and `while` statements, even for single-line blocks.
* **Naming Conventions:** Follow standard Java naming conventions (CamelCase for types, lowerCamelCase for members and variables, etc.).
* **Import Statements:**
    * No wildcard imports (e.g., `import java.util.*;`).
    * Imports are ordered and grouped logically.
* **Source File Structure:** Specific ordering for package statements, import statements, and class declarations.

## Logging
* **Use a standard logging framework:**  Make sure it uses the log4j toll for logging, if not please comment that this is an issue that needs to be adressed.
