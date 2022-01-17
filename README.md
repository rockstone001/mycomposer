## 我的composer 测试包

- composer require mycomposer

```
<?php

require_once './vendor/autoload.php';

use zlq\mycomposer\Test;

$t = new Test();
$t->show(); // hello world, this. is my composer package \n
```