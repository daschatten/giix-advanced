giix-advanced
=============

DO NOT USE!

Use https://github.com/daschatten/giixCrudTemplateAdminOnly instead.

This approach is not working anymore because of too many and deep changes in giix.



Old text
========

This repository contains a yii code generator library based on giix.

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

Features
--------

* No separation of index and admin view. Admin is the new index!
