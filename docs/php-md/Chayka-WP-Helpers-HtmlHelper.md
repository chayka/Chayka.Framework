Chayka\WP\Helpers\HtmlHelper
===============






* Class name: HtmlHelper
* Namespace: Chayka\WP\Helpers
* Parent class: [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)





Properties
----------


### $meta

    protected mixed $meta = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### setPost

    mixed Chayka\WP\Helpers\HtmlHelper::setPost(integer|object|\Chayka\WP\Models\PostModel $post)

Set all the html page title and meta data, based on post information



* Visibility: **public**
* This method is **static**.


#### Arguments
* $post **integer|object|[integer](Chayka-WP-Models-PostModel.md)**



### setSidebarId

    mixed Chayka\WP\Helpers\HtmlHelper::setSidebarId($id)

Set sidebar id for the page responded



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### getSidebarId

    mixed|string Chayka\WP\Helpers\HtmlHelper::getSidebarId()

Set sidebar id for the page responded



* Visibility: **public**
* This method is **static**.




### setMeta

    mixed Chayka\Helpers\HtmlHelper::setMeta(string $key, mixed $value)

A setter for meta container



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $key **string**
* $value **mixed**



### getMeta

    mixed|string Chayka\Helpers\HtmlHelper::getMeta($key, string $default)

A getter for meta container



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $key **mixed**
* $default **string**



### setHeadTitle

    mixed Chayka\Helpers\HtmlHelper::setHeadTitle(string $title)

Store html > head > title value



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $title **string**



### getHeadTitle

    string Chayka\Helpers\HtmlHelper::getHeadTitle(string $default)

Retrieve html > head > title value



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $default **string**



### setMetaKeywords

    mixed Chayka\Helpers\HtmlHelper::setMetaKeywords(string $value)

Store html > head > meta > keywords value



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $value **string**



### getMetaKeywords

    string Chayka\Helpers\HtmlHelper::getMetaKeywords(string $default)

Retrieve html > head > meta > keywords value



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $default **string**



### setMetaDescription

    mixed Chayka\Helpers\HtmlHelper::setMetaDescription(string $value)

Store html > head > meta > description value



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $value **string**



### getMetaDescription

    string Chayka\Helpers\HtmlHelper::getMetaDescription(string $default)

Store html > head > meta > description value



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $default **string**



### hidden

    mixed Chayka\Helpers\HtmlHelper::hidden(boolean $condition)

Output 'style="display: none;"' if $condition truthy



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $condition **boolean**



### visible

    mixed Chayka\Helpers\HtmlHelper::visible(boolean $condition)

Output 'style="display: none;"' if $condition truthy



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $condition **boolean**



### checked

    mixed Chayka\Helpers\HtmlHelper::checked(boolean $condition)

Output 'checked="checked"' if $condition truthy



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $condition **boolean**



### disabled

    mixed Chayka\Helpers\HtmlHelper::disabled(boolean $condition)

Output 'disabled="disabled"' if $condition truthy



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\HtmlHelper](Chayka-Helpers-HtmlHelper.md)


#### Arguments
* $condition **boolean**


