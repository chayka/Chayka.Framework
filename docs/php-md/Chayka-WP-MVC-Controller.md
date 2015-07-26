Chayka\WP\MVC\Controller
===============






* Class name: Controller
* Namespace: Chayka\WP\MVC
* Parent class: [Chayka\MVC\Controller](Chayka-MVC-Controller.md)





Properties
----------


### $appUrl

    protected mixed $appUrl





* Visibility: **protected**


### $view

    protected mixed $view





* Visibility: **protected**


### $appPath

    protected mixed $appPath





* Visibility: **protected**


### $application

    protected mixed $application





* Visibility: **protected**


### $forwardedRequest

    protected mixed $forwardedRequest = null





* Visibility: **protected**


Methods
-------


### __construct

    mixed Chayka\MVC\Controller::__construct(\Chayka\MVC\Application $application)

Controller constructor



* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $application **[Chayka\MVC\Application](Chayka-MVC-Application.md)**



### setPost

    mixed Chayka\WP\MVC\Controller::setPost($post)

This function should be used to set post data,
that will be use later in Chayka\WP\Query and Chayka\WP|Helpers\HtmlHelper.

Long story short, data from the post provide will be used for html title, keywords, description.

* Visibility: **public**


#### Arguments
* $post **mixed**



### setNotFound404

    boolean Chayka\WP\MVC\Controller::setNotFound404(boolean $notFound)

A helper to start 'not found' scenario.

Just return it from controller action at the point when post is not found.

* Visibility: **public**


#### Arguments
* $notFound **boolean**



### setTitle

    mixed Chayka\WP\MVC\Controller::setTitle($title)

Set html title.

Use Chayka\WP|Helpers\HtmlHelper::getHeadTitle() to fetch it in your template.

* Visibility: **public**


#### Arguments
* $title **mixed**



### setDescription

    mixed Chayka\WP\MVC\Controller::setDescription($description)

Set html description.

Use Chayka\WP|Helpers\HtmlHelper::getMetaDescription() to fetch it in your template.

* Visibility: **public**


#### Arguments
* $description **mixed**



### setKeywords

    mixed Chayka\WP\MVC\Controller::setKeywords($keywords)

Set html keywords.

Use Chayka\WP|Helpers\HtmlHelper::getMetaDescription() to fetch it in your template.

* Visibility: **public**


#### Arguments
* $keywords **mixed**



### enqueueScript

    mixed Chayka\WP\MVC\Controller::enqueueScript($handle, string|boolean $resRelativeSrc, array $dependencies, string|boolean $ver, boolean $in_footer)

Enqueue script. Utilizes wp_enqueue_script().

However if detects registered minimized and concatenated version enqueue it instead.

* Visibility: **public**


#### Arguments
* $handle **mixed**
* $resRelativeSrc **string|boolean**
* $dependencies **array**
* $ver **string|boolean**
* $in_footer **boolean**



### enqueueNgScript

    mixed Chayka\WP\MVC\Controller::enqueueNgScript($handle, boolean $resRelativeSrc, array $dependencies, boolean $ver, boolean $in_footer)





* Visibility: **public**


#### Arguments
* $handle **mixed**
* $resRelativeSrc **boolean**
* $dependencies **array**
* $ver **boolean**
* $in_footer **boolean**



### enqueueStyle

    mixed Chayka\WP\MVC\Controller::enqueueStyle($handle, string|boolean $resRelativeSrc, array $dependencies, string|boolean $ver, boolean $in_footer)

Enqueue style. Utilizes wp_enqueue_style().

However if detects registered minimized and concatenated version enqueue it instead.

* Visibility: **public**


#### Arguments
* $handle **mixed**
* $resRelativeSrc **string|boolean**
* $dependencies **array**
* $ver **string|boolean**
* $in_footer **boolean**



### enqueueScriptStyle

    mixed Chayka\WP\MVC\Controller::enqueueScriptStyle(string $handle)

Enqueue both script and style with the same $handle.

Uses minimized versions if detects.

* Visibility: **public**


#### Arguments
* $handle **string**



### enqueueNgScriptStyle

    mixed Chayka\WP\MVC\Controller::enqueueNgScriptStyle($handle)





* Visibility: **public**


#### Arguments
* $handle **mixed**



### loadActionPost

    \Chayka\WP\Models\PostModel|null Chayka\WP\MVC\Controller::loadActionPost($id, $slug, boolean $incReviews)

This helper load post for the action.

It checks if $id and $slug are valid, redirects to valid url otherwise.
If $id or $slug is omitted then loads by what is given and no consistency check is performed.
Assigns post for major $wp_query as current (for all those headers to work right).
And optionally increases post reviews count.

* Visibility: **public**


#### Arguments
* $id **mixed**
* $slug **mixed**
* $incReviews **boolean**



### setupPaginationByWpQuery

    \Chayka\WP\MVC\Controller Chayka\WP\MVC\Controller::setupPaginationByWpQuery(\WP_Query $wpQuery)

Setup pagination by WP_Query



* Visibility: **public**


#### Arguments
* $wpQuery **WP_Query**



### setWpTemplate

    mixed Chayka\WP\MVC\Controller::setWpTemplate($template)

Set WP page template



* Visibility: **public**


#### Arguments
* $template **mixed**



### init

    mixed Chayka\MVC\Controller::init()

This function is called before action is dispatched.

You can override it to create some custom initialization

* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)




### dispatch

    null|string Chayka\MVC\Controller::dispatch(array $request, \Chayka\MVC\View $forwardedView)

Dispatch request.

Request is formed by Application.
This function finds appropriate action callback and invokes it

* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $request **array**
* $forwardedView **[Chayka\MVC\View](Chayka-MVC-View.md)**



### forward

    boolean Chayka\MVC\Controller::forward($action, string $controller)

After dispatching current action forwards processing to specified action controller.



* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $action **mixed**
* $controller **string**



### getApplication

    \Chayka\MVC\Application Chayka\MVC\Controller::getApplication()





* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)




### path2action

    string Chayka\MVC\Controller::path2action($path)

Convert action path string to callback name



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $path **mixed**



### path2controller

    string Chayka\MVC\Controller::path2controller($path)

Convert controller path string to controller classname



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $path **mixed**



### action2path

    string Chayka\MVC\Controller::action2path($action)

Convert action callback name to path string



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $action **mixed**



### controller2path

    string Chayka\MVC\Controller::controller2path($controller)

Convert controller classname to path string



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $controller **mixed**



### getPagination

    \Chayka\MVC\Pagination Chayka\MVC\Controller::getPagination($templatePath)

Get Pagination singleton instance



* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $templatePath **mixed**


