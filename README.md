csi3130_project
===============

Files to be submitted at the end: `createplan.c`, `nodeHash.c`, `execnodes.h` and `nodeHashjoin.c`

Part 1 todo: submit these two files:

- createplan.c
	  - modify `create_hashjoin_plan()`

- nodehash.c
	  - modify `ExecHash()` - complete implementation -> done
	  - modify `ExecHashTableCreate()` - disable batch implementation -> done
	  - modify `ExecScanHashBucket()`
        - check for inner/outer table and load specific values to the hash table. -> done
        - Return value will be changed to `HashTuple` instead of `HeapTuple` -> done
