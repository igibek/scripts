### Export data from Mongo as csv
```shell
mongoexport --db <dbname> --collection <collection name> --type=csv --fields=<comma separated field names>
```