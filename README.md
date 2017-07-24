PHP Git Log Parser
==================
[![Build Status](https://travis-ci.org/tivie/php-git-log-parser.svg)](https://travis-ci.org/tivie/php-git-log-parser) [![Latest Stable Version](https://poser.pugx.org/tivie/php-git-log-parser/v/stable.svg)](https://packagist.org/packages/tivie/php-git-log-parser) [![License](https://poser.pugx.org/tivie/php-git-log-parser/license.svg)](https://packagist.org/packages/tivie/php-git-log-parser) 

A parser, written in PHP, for logs generated by git log

## Installation
You can install it by cloning the git repository or using composer.

### Git clone

    git clone https://github.com/tivie/php-git-log-parser.git

### Composer
Add these lines to your composer.json:
```json
    {
        "require": {
            "tivie/php-git-log-parser": "*"
        }
    }
```
or run the following command:

    php composer.phar require tivie/php-git-log-parser

## Quick guide
To parse the current git repository log, you can simply

```php
$parser = new \Tivie\GitLogParser\Parser();
$logArray = $parser->parse();
```

## License
PHP Git Log Parser is released under Apache 2.0 license. For more information, please consult the [LICENSE](https://github.com/tivie/php-git-log-parser/blob/master/LICENSE) file in this repository or http://www.apache.org/licenses/LICENSE-2.0.txt.
