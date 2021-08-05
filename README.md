# kvrangedb YCSB Binding

This repository provide leveldb YCSB binding (Binary Only)

# Run

## Setup environment

In env_setup.sh, change **LIB_HOME** to your leveldb project path.

## Setup kvrangedb configuration

Modify leveldb_config.json.

## Run ycsb workload

```bash
  ./bin/ycsb load leveldb -s -P workloads/test_scan # load data
  ./bin/ycsb run leveldb -s -P workloads/test_scan # run queries
```

# TODO

Complete the leveldb code (with different configurations)

Run script for all the test


