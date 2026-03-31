# FQCN Extractor

A lightweight PHP utility to extract the Fully Qualified Class Name (FQCN) from a PHP source file using the built-in tokenizer.

## Installation

```bash
composer require jawitold/fqcn-extractor
```

## Usage

```php
use JaWitold\FqcnExtractor\FqcnExtractor;

$extractor = new FqcnExtractor();
$fqcn = $extractor->extract('path/to/file.php');

// Returns something like: My\Namespace\MyClass
echo $fqcn;
```

## Requirements

- PHP 8.1+
- PHP `tokenizer` extension (built-in by default)

## License

This project is licensed under the MIT License - see the [LICENCE.md](LICENCE.md) file for details.
