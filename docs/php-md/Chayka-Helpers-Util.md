Chayka\Helpers\Util
===============






* Class name: Util
* Namespace: Chayka\Helpers







Methods
-------


### getItem

    mixed Chayka\Helpers\Util::getItem($data, $key, $defaultValue)

Returns object's property or array's element by key
in case of absense returns default value



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **mixed**
* $key **mixed**
* $defaultValue **mixed**



### print_r

    integer Chayka\Helpers\Util::print_r(mixed $var)

Alias of print_r(), but encloses output into <pre>.

..</pre>

* Visibility: **public**
* This method is **static**.


#### Arguments
* $var **mixed**



### serverName

    mixed Chayka\Helpers\Util::serverName()

Get server name from $_SERVER['SERVER_NAME'] without 'www.'



* Visibility: **public**
* This method is **static**.




### sessionStart

    mixed Chayka\Helpers\Util::sessionStart()

Start session.



* Visibility: **public**
* This method is **static**.




### translit

    mixed Chayka\Helpers\Util::translit($str)

Perform translit convert of cyrillic string



* Visibility: **public**
* This method is **static**.


#### Arguments
* $str **mixed**



### cmpVersion

    integer Chayka\Helpers\Util::cmpVersion($a, $b)

Compares to version strings



* Visibility: **public**
* This method is **static**.


#### Arguments
* $a **mixed**
* $b **mixed**


