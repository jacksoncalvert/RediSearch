Returns a list of all existing indexes.

!!! note "Temporary command"
    The prefix `_` in the command indicates, this is a temporary command.

    In the future, a `SCAN` type of command will be added, for use when a database
    contains a large number of indices.

@return

@array-reply with index names.

@examples

```sql
FT._LIST
1) "idx"
2) "movies"
3) "imdb"
```