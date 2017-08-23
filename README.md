# Chinese Lunar Calendar

Converts from Gregorian date to Chinese lunisolar date and vice versa. Accepts dates between the years 1900-2100.

## Usage

```php
use peterkahl\Lunar\Lunar;

$gregorianDate = date('Y-m-d'); # '2017-08-23'

$chineseDate = Lunar::Gregorian2Lunar($gregorianDate);

/*
array(7) {
  ["y"]=>
  int(2017)
  ["m"]=>
  int(7)
  ["d"]=>
  int(2)
  ["leap"]=>
  bool(false)
  ["zh-cn"]=>
  string(12) "七月初二"
  ["zh-hk"]=>
  string(12) "七月初二"
  ["ja"]=>
  string(12) "七月初二"
  ["en"]=>
  string(5) "07-02"
}
*/
```
