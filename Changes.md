<<<<<<< HEAD
## 1.1.0 - 2016-10-19

* Fail loudly if any configured `MaxMindDBFile`s don't exist.
  Previously we would accept the configuration and silently do nothing.
* Support lookups in the root of VHost sections.
* `MaxMindDBEnv` now takes exactly two arguments. Previously, it allowed more
  arguments but ignored all but one set of arguments.

=======
>>>>>>> parent of 4f94610... Update changelog
## 1.0.1 - 2015-03-16

* The module is now compiled with the `-std=c99 -fms-extensions` flags. This
  fixes compilation errors on older version of `gcc`.

## 1.0.0 - 2015-01-02

* First non-beta release.
* Updated documentation for completeness and correctness.
* Added maxminddb.h check to configure.ac.

## 0.2.0 - 2014-12-10

* The `MaxMindDBEnable` directive was changed from `OR_FILEINFO` to `OR_ALL`.
  The directive will now work anywhere and does not require
  `AllowOverride FileInfo` to work in an `.htaccess` file.

## 0.1.0 - 2014-11-17

* The module was largely rewritten. It now supports configuration contexts
  and handles configuration merging.

## 0.0.1 - 2014-02-12

* Initial release.
