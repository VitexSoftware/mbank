![EasePHP Framework Logo](https://raw.githubusercontent.com/VitexSoftware/mbank/master/project-logo.png "Project Logo")
## Library for accessing mBank PL/CZ/SK transaction service

( Forked from [bgaluszka/mbank](https://github.com/bgaluszka/mbank) )

 Suitable for checking for new transactions. Supported features:

 * list available accounts, 
 * list recent operations on the accounts,
 * MT940 support (requires mBank's MT940 reports to be enabled for the account)
   * MT940 file report fetch for specified date range
   * MT940 based transaction summary for specified date range

## Requirements

 * PHP 5.3 or higher
 * Extensions:
   * [cURL](http://www.php.net/manual/book.curl.php) 
   * [DOM](http://php.net/manual/en/book.dom.php) 

## Installation

Install library from composer:

    {
        "require": {
            "vitexsoftware/mbank": "dev-master"
        }
    }

## Usage examples

For usage examples, please see scripts in [examples/](examples/) directory. 

