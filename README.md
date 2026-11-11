# Zongtian Hou

Database kernel engineer. Nine years in software, seven of them inside database engines.

## What I work on

- **Query optimization** - planner and optimizer rules, execution-time partition pruning, index and sort-elimination work
- **Execution** - parallel index and bitmap scans, hash joins, asynchronous parallel operators
- **Storage and distribution** - columnar formats (Arrow, ORC), object-storage query paths, MPP sharding and replication

## Open source

**Apache HAWQ** - 44 commits, 2019-2020 ([commit history](https://github.com/search?q=repo%3Aapache%2Fhawq+author-email%3Ahouzongtian%40outlook.com&type=commits))

ORC reader and writer for the vectorized executor (decimal encoding, type checks, null-file handling);
type-system functions for timestamptz, interval, numeric and bytea; Vector/TupleBatch refactor and group
aggregation; FlatMemBuf allocation strategy, lock waiter lists and memory accounting.

## Toolbox

`C/C++` · `Python` · `SQL` - PostgreSQL, Greenplum, openGauss, HAWQ

## About this profile

Most of my work lives in proprietary engines and cannot be published. The commits above predate the
account in use here, so GitHub links them to an earlier handle; the authored name and address are on
every commit.

Contact: markmonkey91@gmail.com
