# Readable Random String

Creates a random (as far as Math.random is random) string that is readable for humans.
This can be used to generate usernames or small links that can be more easily remembered.

Avoid using this for passwords, because it is not secure (generate strings contains only lowercase letters).

## usage

```javascript
import rrs from 'readable-random-string';

rrs(5);
// "uthek"
```

## parameters

#### `length`: number

Length of returned string.

#### `separatorGap`: number (default: 0)

Return string separated by dashes ervery `separatorGap` characters.

exemple :
    
```javascript
rrs(9, 4);
// "mela-ekou"
```

## Licence

Licensed under MIT license, Copyright © 2022 CELLARIER Arno
