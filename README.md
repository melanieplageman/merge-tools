To run the tests:

```
./test_merge
```

To use the merge utility for creating the merge commit at the end of an iteration, copy the merge utility into the GPDB repository and do the following:

Checkout a branch for the merge
```
git checkout origin/master -b iteration_<iteration number>_rebased
```

Run the merge utility
```
./merge <Postgres commit id> iteration_<iteration number>
```

Follow the instructions to write the commit message
