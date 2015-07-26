Chayka\MVC\View
===============






* Class name: View
* Namespace: Chayka\MVC





Properties
----------


### $vars

    protected mixed $vars = array()





* Visibility: **protected**


### $basePaths

    protected mixed $basePaths = array('')





* Visibility: **protected**


### $path

    protected mixed $path = ''





* Visibility: **protected**


### $nls

    protected mixed $nls = false





* Visibility: **protected**


Methods
-------


### declareVars

    mixed Chayka\MVC\View::declareVars($vars)

Declare defaults var values, can be called



* Visibility: **public**


#### Arguments
* $vars **mixed**



### escape

    string Chayka\MVC\View::escape($value, boolean $output)

Escape $value and output it



* Visibility: **public**


#### Arguments
* $value **mixed**
* $output **boolean**



### addBasePath

    mixed Chayka\MVC\View::addBasePath($basePath)

Add path to look for templates



* Visibility: **public**


#### Arguments
* $basePath **mixed**



### render

    null|string Chayka\MVC\View::render(string $path, array $vars)

Render .phtml template



* Visibility: **public**


#### Arguments
* $path **string**
* $vars **array**



### partial

    null|string Chayka\MVC\View::partial($path, $vars)

Render template with defined scope



* Visibility: **public**


#### Arguments
* $path **mixed**
* $vars **mixed**



### enableNls

    mixed Chayka\MVC\View::enableNls(boolean $enable)

If turned on, when rendered, view will search localized version of template.

E.g. 'auth.en.phtml' if 'auth.phtml' requested.

* Visibility: **public**


#### Arguments
* $enable **boolean**



### _

    string Chayka\MVC\View::_(string $value)

Get localized value, or value itself if localization is not found
This function can get multiple args and work like sprintf($template, $arg1, .

.. $argN)
Hint: Use $format = 'На %2$s сидят %1$d обезьян';

* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **string** - &lt;p&gt;String to translate&lt;/p&gt;



### __

    string Chayka\MVC\View::__(string $value)

Echo localized value, or value itself if localization is not found
This function can get multiple args and work like sprintf($template, $arg1, .

.. $argN)
Hint: Use $format = 'На %2$s сидят %1$d обезьян';

* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **string** - &lt;p&gt;String to translate&lt;/p&gt;



### assign

    mixed Chayka\MVC\View::assign($key, $value)

Assign template var.

$this->var = 'value' can be used.

* Visibility: **public**


#### Arguments
* $key **mixed**
* $value **mixed**



### __set

    mixed Chayka\MVC\View::__set($key, $value)

Magic var setter



* Visibility: **public**


#### Arguments
* $key **mixed**
* $value **mixed**



### __get

    mixed Chayka\MVC\View::__get($key)

Magic var getter



* Visibility: **public**


#### Arguments
* $key **mixed**



### htmlAttributes

    string Chayka\MVC\View::htmlAttributes(array $attributes)

Transform key=>value array to key="value" attributes string



* Visibility: **public**


#### Arguments
* $attributes **array**



### formInput

    string Chayka\MVC\View::formInput(string $name, string $value, $type, array $attributes)

Generate html input element.



* Visibility: **public**


#### Arguments
* $name **string**
* $value **string**
* $type **mixed**
* $attributes **array**



### formCheckbox

    string Chayka\MVC\View::formCheckbox(string $name, string $value, string $checked, string $unchecked, array $attributes)

Generate html input[type=checkbox] element.



* Visibility: **public**


#### Arguments
* $name **string**
* $value **string**
* $checked **string**
* $unchecked **string**
* $attributes **array**



### formRadio

    string Chayka\MVC\View::formRadio(string $name, string $value, array $options, array $attributes, string $separator)

Generate set of html input[type=radio] elements.



* Visibility: **public**


#### Arguments
* $name **string**
* $value **string**
* $options **array**
* $attributes **array**
* $separator **string**



### formSelect

    string Chayka\MVC\View::formSelect(string $name, string $value, array $options, array $attributes)

Generate html select element.



* Visibility: **public**


#### Arguments
* $name **string**
* $value **string**
* $options **array**
* $attributes **array**



### formTextarea

    string Chayka\MVC\View::formTextarea($name, $value, $attributes)

Generate html textarea element.



* Visibility: **public**


#### Arguments
* $name **mixed**
* $value **mixed**
* $attributes **mixed**



### hidden

    mixed Chayka\MVC\View::hidden(boolean $condition)

Output 'style="display: none;"' if $condition truthy



* Visibility: **public**
* This method is **static**.


#### Arguments
* $condition **boolean**



### visible

    mixed Chayka\MVC\View::visible(boolean $condition)

Output 'style="display: none;"' if $condition truthy



* Visibility: **public**
* This method is **static**.


#### Arguments
* $condition **boolean**



### checked

    mixed Chayka\MVC\View::checked(boolean $condition)

Output 'checked="checked"' if $condition truthy



* Visibility: **public**
* This method is **static**.


#### Arguments
* $condition **boolean**



### disabled

    mixed Chayka\MVC\View::disabled(boolean $condition)

Output 'disabled="disabled"' if $condition truthy



* Visibility: **public**
* This method is **static**.


#### Arguments
* $condition **boolean**



### getPagination

    \Chayka\MVC\Pagination Chayka\MVC\View::getPagination($templatePath)

Get Pagination singleton instance



* Visibility: **public**


#### Arguments
* $templatePath **mixed**


