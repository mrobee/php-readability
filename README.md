php-readability
===============

PHP Readability fork from http://code.fivefilters.org/p/php-readability/

the getContent() function return just text without HTML tags.

Usage
-----

$doc = new Readability();
$doc->input('http://google.com');
$doc->init();
$content = $doc->getContent();