Change Log
==========

v0.5.0 - coming
===============

-	Support for `cflinuxfs2` trusty stack (and continued support for `lucid64` stack) [thanks @simonjohansson]
-	Remove trailing whitespace from Staticfile 'root:' value [thanks @edmorley]

### Testing buildpacks

There is now a basic test harness script in `tests/test.sh`.

To test a branch on github:

```
ORG=edmorley BRANCH="root_dir-whitespace" ./test/test.sh
```