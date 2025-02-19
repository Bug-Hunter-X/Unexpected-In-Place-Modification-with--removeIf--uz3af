# Kotlin `removeIf` Gotcha

This example demonstrates a subtle but potentially problematic aspect of the `removeIf` function in Kotlin.  Unlike some other collection methods that return a new collection, `removeIf` directly modifies the original collection in place.

The `bug.kt` file shows the unexpected behavior.  The solution in `bugSolution.kt` demonstrates how to achieve the desired behavior (creating a new collection without modifying the original) using methods that return a new collection.
