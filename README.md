To reproduce
============

1. Run `./gradlew jar`

Expected
========

It makes a jar

Actual
======

```
> Task :processResources FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':processResources'.
> Cannot convert URL 'foo:bar.json' to a file.
```
