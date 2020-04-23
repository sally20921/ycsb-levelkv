# kvrangedb YCSB Binding

This repository provide kvrangedb YCSB binding (Binary Only)

# Run

## Setup environment

In env_setup.sh, change **LIB_HOME** to your kvrangedb project path.

## Setup kvrangedb configuration

Modify kvrangedb_config.json.

## Run ycsb workload

```bash
  ./bin/ycsb load kvrangedb -s -P workloads/test_scan # load data
  ./bin/ycsb run kvrangedb -s -P workloads/test_scan # run queries
```

# TODO

Complete the kvrangedb code (with different configurations)

Run script for all the test


