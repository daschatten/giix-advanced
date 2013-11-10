giix-crud-advanced
=============

This repository contains yii code generator library based on giix.

Requirements
------------

* Yii http://www.yiiframework.com
* giix http://www.yiiframework.com/extension/giix

Installation
------------

1. Clone repository in the 'extensions' folder of your yii application
2. Add giix-advanced to the application configuration:
```php
...
'gii'=>array(
            ...
            'generatorPaths' => array('ext.giix.generators', 'ext.giix-advanced.generators'),
        ),
...
```
