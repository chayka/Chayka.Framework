Chayka\WP\Helpers\AngularHelper
===============






* Class name: AngularHelper
* Namespace: Chayka\WP\Helpers
* Parent class: [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)





Properties
----------


### $registered

    public \Chayka\WP\Helpers\[string] $registered = array()





* Visibility: **public**
* This property is **static**.


### $callbacks

    public \Chayka\WP\Helpers\[callback] $callbacks = array()





* Visibility: **public**
* This property is **static**.


### $queue

    public \Chayka\WP\Helpers\[string] $queue = array()





* Visibility: **public**
* This property is **static**.


### $dependencies

    public array<mixed,> $dependencies = array()





* Visibility: **public**
* This property is **static**.


### $isMediaMinimized

    protected mixed $isMediaMinimized = false





* Visibility: **protected**
* This property is **static**.


### $minimizedStyles

    protected mixed $minimizedStyles = array()





* Visibility: **protected**
* This property is **static**.


### $minimizedScripts

    protected mixed $minimizedScripts = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### registerScript

    mixed Chayka\WP\Helpers\ResourceHelper::registerScript(string $handle, string $src, array $dependencies, boolean $version, boolean $inFooter)

Alias to wp_register_script but checks if dependencies can be found inside minimized files



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $handle **string**
* $src **string**
* $dependencies **array**
* $version **boolean**
* $inFooter **boolean**



### enqueueScript

    mixed Chayka\WP\Helpers\ResourceHelper::enqueueScript($handle, string|boolean $src, array $dependencies, string|boolean $ver, boolean $inFooter)

Enqueue script. Utilizes wp_enqueue_script().

However if detects registered minimized and concatenated version enqueue it instead.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $handle **mixed**
* $src **string|boolean**
* $dependencies **array**
* $ver **string|boolean**
* $inFooter **boolean**



### getQueue

    mixed Chayka\WP\Helpers\AngularHelper::getQueue()





* Visibility: **public**
* This method is **static**.




### isMediaMinimized

    boolean Chayka\WP\Helpers\ResourceHelper::isMediaMinimized()





* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)




### setMediaMinimized

    mixed Chayka\WP\Helpers\ResourceHelper::setMediaMinimized(boolean $isMediaMinimized)





* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $isMediaMinimized **boolean**



### registerMinimizedScript

    mixed Chayka\WP\Helpers\ResourceHelper::registerMinimizedScript(string $minHandle, string $src, array $handles, boolean $version, boolean $inFooter)

Register script that contains minimized and concatenated scripts



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $minHandle **string**
* $src **string**
* $handles **array**
* $version **boolean**
* $inFooter **boolean**



### setScriptLocation

    mixed Chayka\WP\Helpers\ResourceHelper::setScriptLocation($handle, boolean $inFooter)

This function can change default script rendering location: head or footer



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $handle **mixed**
* $inFooter **boolean**



### registerStyle

    mixed Chayka\WP\Helpers\ResourceHelper::registerStyle(string $handle, string $src, array $dependencies, boolean $version, string $media)

Alias to wp_register_style but checks if dependencies can be found inside minimized files



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $handle **string**
* $src **string**
* $dependencies **array**
* $version **boolean**
* $media **string**



### registerMinimizedStyle

    mixed Chayka\WP\Helpers\ResourceHelper::registerMinimizedStyle(string $minHandle, string $src, array $handles, boolean $version, string $media)

Register script that contains minimized and concatenated styles



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $minHandle **string**
* $src **string**
* $handles **array**
* $version **boolean**
* $media **string**



### enqueueStyle

    mixed Chayka\WP\Helpers\ResourceHelper::enqueueStyle($handle, string|boolean $src, array $dependencies, string|boolean $ver, string $media)

Enqueue style. Utilizes wp_enqueue_style().

However if detects registered minimized and concatenated version enqueue it instead.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $handle **mixed**
* $src **string|boolean**
* $dependencies **array**
* $ver **string|boolean**
* $media **string**



### enqueueScriptStyle

    mixed Chayka\WP\Helpers\ResourceHelper::enqueueScriptStyle(string $handle, boolean $scriptInFooter)

Enqueue both script and style with the same $handle.

Uses minimized versions if detects.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\ResourceHelper](Chayka-WP-Helpers-ResourceHelper.md)


#### Arguments
* $handle **string**
* $scriptInFooter **boolean**


