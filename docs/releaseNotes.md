# Semantic versioning

```
va.b.c
```

* a: major version. Big changes in implementation or release status
* b: minor version. Incremental feature upgrades within major release
* c: bugfix version. As needed to fix bugs in current minor release

# Release Notes v1.01



* Added auto-update and exams in progress reminders. 
* Improved interlocks.
* Upgraded Fable to 2.0.0-beta-004

NB Fable numbers are now working properly (bitwise ops and conversions work as expected), also exact numbers semantics has been documented and linked from documentation.

# Release notes v1.00


* v1.00 is similar in functionality to 0.x but is the first production release.
* Assembly simulator semantics. Some adjustment to improve the (badly documented) behaviour of carry which is written when a literal 
is selected for op2 that is larger than 255 in a non-arithmetic data processing instruction. Note that VisUAL got
this wrong, so the tests against Visual that error under Visual2 are marked allowed.

