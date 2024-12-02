# sql2tree

A CLI wrapper around the `pg_query_go` `ParseToJSON` function.

## Usage

```bash
go install github.com/andrew-farries/sql2tree@latest
sql2tree "CREATE TABLE foo(a int)" | jq
```
