# postmigrate

A barebone PostgreSQL schema migration tool

# Usage

 * Create your `init/init.sql` script to initialize the database.
 * Create your `config.rb` with DB host / database name / user

```shell
# initialize the database environment
./migrate init

# create a new version of migration
./migrate new <your description here>

# update to newest version
./migrate up
```

# Note

 * Please add `.current` and `config.rb` into your version control ignore list.
