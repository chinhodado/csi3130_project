csi3130_project
===============

To see all changes to the original code, click [here](https://github.com/chinhodado/csi3130_project/compare/8d0c66888fa87c539813380184c5f117ba2a81fa...master)

Files to be submitted at the end: `createplan.c`, `nodeHash.c`, `execnodes.h` and `nodeHashjoin.c`

Part 1 todo: submit these two files:

- createplan.c
	  - modify `create_hashjoin_plan()` -> done

- nodehash.c
	  - modify `ExecHash()` - complete implementation -> done
	  - modify `ExecHashTableCreate()` - disable batch implementation -> done
	  - modify `ExecScanHashBucket()`
        - check for inner/outer table and load specific values to the hash table. -> done
        - Return value will be changed to `HashTuple` instead of `HeapTuple` -> done
