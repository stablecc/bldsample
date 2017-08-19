# bldsample

Build sample using the https://github.com/stablecc make system and import library.

Build and run rapidxml unit:
```
$ cd import/rapidxml/unittest
$ make
...
$ LD_LIBRARY_PATH=bin/ bin/gtest_all_test_d
```

Build and run googletest unit:
```
$ cd import/rapidxml/unittest
$ make
...
$ LD_LIBRARY_PATH=../../../bin ../../../bin/gtest_all_test_d
```
