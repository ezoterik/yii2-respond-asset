Respond.js asset for Yii2 framework
===============================

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist ezoterik/yii2-respond-asset "*"
```

or add

```
"ezoterik/yii2-respond-asset": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Register Respond.js in your *views* with:
 ```php
 ezoterik\respondAsset\RespondAsset::register($this);
 ```

Or set a dependancy in your AppAsset with:
 ```php
 public $depends = [
     // ...
     'ezoterik\respondAsset\RespondAsset',
     // ...
 ];
 ```