# Release Notes v1.00

### Semantic versioning

```
va.b.c
```

* a: major version. Big changes in in implementation or release status
* b: minor version. Incrmental feature upgrades within major release
* c: bugfix version. As needed to fix bugs in current minor release

## Changes from v0.14

v1.00 is similar in functionality to 0.x but is the first production release.

### Assembly simulator semantics

Some adjustment to improve the (badly documented) behaviour of carry which is written when a literal 
is selected for op2 that is larger than 255 in a non-arithmetic data processing instruction. Note that VisUAL got
this wrong, so the tests against Visual that error under visual2 are marked allowed.

