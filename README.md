AssetFix CLI for Joomla! 3.0
============================

Performance fix of fixContentAssets() method, added loop with limited by 100 queries from jos_content table.  
AssetFix is a CLI script that rewrite your #__assets table preventing errors and slow speed of load caused by bad migrations or
end user manual manipulation of the tables. This scripts try to offer a way to solve that problem.

## Installation

Only copy this files to Joomla! CLI folder.

## Usage

Access the CLI folder of Joomla! and run the command: php assetfix.php

## Authors

* Matias Aguirre (Original Author)
* Bruno Batista

## License

Licensed under the terms of the MIT license.

## Bugs/Requests

* You can [report a bug or request a feature here](http://github.com/brunobatista/cli_assetfix/issues)