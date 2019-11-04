# python-sqlite-cache

SQlite Cache module

## Requirements

- Python 3.6+

## Install

~~~
$ pip install python-sqlite-cache
~~~

## Usage

### Initialize

#### In Memory

~~~
> from sqlite_cache.sqlite_cache import SqliteCache
> sql_cache = SqliteCache()
~~~

#### On Disk

~~~
> from sqlite_cache.sqlite_cache import SqliteCache
> sql_cache = SqliteCache(path_cache_dir)
~~~

### Usage

~~~
> sql_cache.set('some_key')
> print(sql_cache_get('some_key', 'some_value'))
some_value
~~~
