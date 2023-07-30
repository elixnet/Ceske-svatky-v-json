# České svátky v JSON
České svátky (jmeniny a státní svátky) podle dnů v roce ve formátu JSON.

## Usage in PHP:

```php
<?php
$jsonFile  = file_get_contents( './src/svatky.json' );
$array     = json_decode( $jsonFile, true );

/**
 * $array[ MONTH ][ DAY ]
 */
echo $array[12][31]; // 'Silvestr'
echo $array[7][30];  // 'Bořivoj'
echo $array[1][1];   // 'Nový rok'
```

## Support
**České svátky** is open source and free. Donate for coffee or just like that:

BTC: `bc1q03v5la7uvcwxr7z4qn03ex6n5edju6zv4n6ppt`

## License
**České svátky** is open source software licensed under the [MIT license](https://tldrlegal.com/license/mit-license).
