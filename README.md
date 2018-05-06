php-simple-html-dom-parser
==========================

Original version from https://github.com/sunra/php-simple-html-dom-parser

Usage
-----

```
composer require vanhoavn/php-simple-html-dom-parser
```

```php
use Vhqtvn\PhpSimple\HtmlDomParser;

...
$dom = HtmlDomParser::str_get_html( $str );
or 
$dom = HtmlDomParser::file_get_html( $file_name );

$elems = $dom->find($elem_name);
...

```
