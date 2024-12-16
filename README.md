# Uninitialized Property Access in C#

This repository demonstrates a common error in C#: accessing a property that hasn't been initialized. This can lead to a `NullReferenceException` if the property is a reference type (like a string or an object) and hasn't been assigned a value.

The `bug.cs` file contains code that exhibits this issue.  The `bugSolution.cs` file shows how to fix the problem by initializing the property.

## How to reproduce the error

1. Clone the repository.
2. Compile and run `bug.cs`.
3. You should observe a `NullReferenceException`.

## How to fix the error

Refer to `bugSolution.cs` for a corrected implementation.