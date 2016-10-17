# Cryptpad level export

## Status

Maintained. Not thoroughly tested.

## Why?

Leveldb is awesome, but it doesn't work across all architectures.

As such, Cryptpad is moving towards using filesystem storage as its default.

If you've installed Cryptpad and would like to migrate the data in your leveldb, this tool is for you.

## Usage

```Bash
# turn off your cryptpad instance

# write your current database to a file
./export /path/to/your/leveldb > cryptpad-level.dump;

# edit your cryptpad/config.js to use the new filestore

# then use cryptpad/import
cd ~/path/to/cryptpad;

./import /path/to/cryptpad-level.dump;

# Launch cryptpad and confirm that your data is available within the new database
```

## License

Available under the AGPL-3.0 license.

