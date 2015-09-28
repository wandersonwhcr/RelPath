RelPath
=======

RelPath is a small PHP library for computing a relative filepath to some path,
either from the current directory or from an optional start directory.

Here is how you use it:

```php

$path = RelPath\getRelativePath( '/srv/mediawiki/resources/src/startup.js', '/srv/mediawiki' );
// Result: string(24) "resources/src/startup.js"

```

License
-------

MIT
