# Groovy NullPointerException in Arithmetic Operations

This example demonstrates a potential issue in Groovy when performing arithmetic operations with variables that might be null.  Groovy's dynamic typing allows null values in expressions, but this can lead to unexpected behavior if not handled properly.

The provided `bug.groovy` file contains a method that attempts to perform addition, returning `null` if either input is null.  However, a developer might expect an exception instead or different null handling behavior.  The solution demonstrates how to explicitly check for null values before proceeding with the calculation.