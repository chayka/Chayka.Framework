Chayka\WP\Helpers\OptionHelper
===============






* Class name: OptionHelper
* Namespace: Chayka\WP\Helpers





Properties
----------


### $cache

    protected mixed $cache = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### getPrefix

    string Chayka\WP\Helpers\OptionHelper::getPrefix()

You can ascend from this class.

You may want to override this class to set custom prefix.

* Visibility: **public**
* This method is **static**.




### getOption

    mixed|void Chayka\WP\Helpers\OptionHelper::getOption(string $option, string $default, boolean $reload)

Alias to get_option but with custom prefix



* Visibility: **public**
* This method is **static**.


#### Arguments
* $option **string**
* $default **string**
* $reload **boolean**



### setOption

    boolean Chayka\WP\Helpers\OptionHelper::setOption(string $option, $value)

Alias to update_option but with custom prefix



* Visibility: **public**
* This method is **static**.


#### Arguments
* $option **string**
* $value **mixed**



### getSiteOption

    mixed Chayka\WP\Helpers\OptionHelper::getSiteOption($option, string $default, boolean $reload)

Alias to get_site_option but with custom prefix



* Visibility: **public**
* This method is **static**.


#### Arguments
* $option **mixed**
* $default **string**
* $reload **boolean**



### setSiteOption

    boolean Chayka\WP\Helpers\OptionHelper::setSiteOption($option, $value)

Alias to get_site_option but with custom prefix



* Visibility: **public**
* This method is **static**.


#### Arguments
* $option **mixed**
* $value **mixed**


