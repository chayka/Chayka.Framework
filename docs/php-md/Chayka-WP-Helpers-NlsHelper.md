Chayka\WP\Helpers\NlsHelper
===============






* Class name: NlsHelper
* Namespace: Chayka\WP\Helpers
* Parent class: [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)





Properties
----------


### $dictionary

    protected mixed $dictionary = array()





* Visibility: **protected**
* This property is **static**.


### $locale

    protected mixed $locale





* Visibility: **protected**
* This property is **static**.


### $lang

    protected mixed $lang





* Visibility: **protected**
* This property is **static**.


### $baseDir

    protected mixed $baseDir





* Visibility: **protected**
* This property is **static**.


### $nlsDir

    protected mixed $nlsDir = 'app/nls/'





* Visibility: **protected**
* This property is **static**.


Methods
-------


### setLocale

    mixed Chayka\Helpers\NlsHelper::setLocale($locale)

Set current locale.

Locale::setDefault() is used.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $locale **mixed**



### getLocale

    string Chayka\Helpers\NlsHelper::getLocale()

Function returns current locale



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)




### setLang

    mixed Chayka\Helpers\NlsHelper::setLang(string $lang)

Set current language



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $lang **string**



### getLang

    string Chayka\Helpers\NlsHelper::getLang()

Get current language



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)




### setBaseDir

    mixed Chayka\Helpers\NlsHelper::setBaseDir(string $dir)

Set base project dir



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $dir **string**



### getBaseDir

    string Chayka\Helpers\NlsHelper::getBaseDir()

Get base project dir



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)




### setNlsDir

    mixed Chayka\Helpers\NlsHelper::setNlsDir(string $dir)

Set nls dir (relative to base dir)



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $dir **string**



### getNlsDir

    string Chayka\Helpers\NlsHelper::getNlsDir()

Get base dir (relative to base dir)



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)




### load

    mixed Chayka\Helpers\NlsHelper::load($module)

Load translation (e.g. 'auth').

Translations can be stored in two alternative paradigms:
1. Split by lang-dirs
nls/
  _/
    auth.php
  en/
    auth.php
2. Split by extension prefix
nls/
  auth.php
  auth._.php
  auth.en.php

'_' - stands for default

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $module **mixed**



### translate

    string Chayka\Helpers\NlsHelper::translate(string $string, string $module)

Search for the translation in all the dictionaries.

Begins with module dictionary if the one specified.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $string **string**
* $module **string**



### _

    string Chayka\Helpers\NlsHelper::_(string $value)

Get localized value, or value itself if localization is not found
This function can get multiple args and work like sprintf($template, $arg1, .

.. $argN)
Hint: Use $format = 'На %2$s сидят %1$d обезьян';

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $value **string** - &lt;p&gt;String to translate&lt;/p&gt;



### __

    string Chayka\Helpers\NlsHelper::__(string $value)

Echo localized value, or value itself if localization is not found
This function can get multiple args and work like sprintf($template, $arg1, .

.. $argN)
Hint: Use $format = 'На %2$s сидят %1$d обезьян';

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\NlsHelper](Chayka-Helpers-NlsHelper.md)


#### Arguments
* $value **string** - &lt;p&gt;String to translate&lt;/p&gt;


