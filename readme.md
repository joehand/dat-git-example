# Dat Sparse Test

A test for how sparse + git work together.

You should be able to get the files via:

```
git clone git@github.com:joehand/dat-clone-sparse-test.git
cd dat-clone-sparse-test
dat sync
dat sync  # run again b/c of bug
```

[This bug](https://github.com/datproject/dat/issues/840) requires you to run `dat sync` twice. I can give pointers to how to fix this if someone wants to PR =).
