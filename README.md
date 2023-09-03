# České svátky v JSON formátu

České svátky (jmeniny a státní svátky) podle dnů v roce ve formátu JSON.

## Použití:

```php
<?php
$jsonFile  = file_get_contents( './src/svatky.json' );
$array     = json_decode( $jsonFile, true );

/**
 * echo $array[ MĚSÍC ][ DEN ]
 */
echo $array[12][31]; // 'Silvestr'
echo $array[7][30];  // 'Bořivoj'
echo $array[1][1];   // 'Nový rok'
```

## Podpora

**České svátky** jsou **open source** a **zdarma**. Podpořte práci autora :

**BTC**: `bc1q03v5la7uvcwxr7z4qn03ex6n5edju6zv4n6ppt`

## Licence

**České svátky** je open source software licencován pod [MIT license](https://tldrlegal.com/license/mit-license).
