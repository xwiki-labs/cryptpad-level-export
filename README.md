# Cryptpad level export

## Status

Maintained.

## Why?

Leveldb is awesome, but it doesn't work across all architectures.

As such, Cryptpad is moving towards using filesystem storage as its default.

If you've installed Cryptpad and would like to migrate the data in your leveldb, this tool is for you.

## Usage

```Bash
./export /path/to/your/leveldb
```

## License

Available under the AGPL-3.0 license.

