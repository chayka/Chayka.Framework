Chayka\WP\MVC\RestController
===============






* Class name: RestController
* Namespace: Chayka\WP\MVC
* Parent class: [Chayka\MVC\RestController](Chayka-MVC-RestController.md)





Properties
----------


### $modelClassName

    protected mixed $modelClassName





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


### getModelClassName

    string Chayka\WP\MVC\RestController::getModelClassName()

Get model classname for this RestController



* Visibility: **public**




### setModelClassName

    mixed Chayka\WP\MVC\RestController::setModelClassName(string $modelClassName)

Set model classname fot this RestController



* Visibility: **public**


#### Arguments
* $modelClassName **string**



### init

    mixed Chayka\MVC\Controller::init()

This function is called before action is dispatched.

You can override it to create some custom initialization

* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)




### createAction

    null Chayka\MVC\RestController::createAction(boolean $respond)

Create entity by issue of POST request



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean** - &lt;p&gt;if true JSON wrapped entity will be responded&lt;/p&gt;



### updateAction

    null Chayka\MVC\RestController::updateAction(boolean $respond)

Update entity by issue of PUT request



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean** - &lt;p&gt;if true JSON wrapped entity will be responded&lt;/p&gt;



### deleteAction

    null Chayka\MVC\RestController::deleteAction(boolean $respond)

Delete entity by issue of DELETE request



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean** - &lt;p&gt;if true JSON wrapped entity will be responded&lt;/p&gt;



### readAction

    null Chayka\MVC\RestController::readAction(boolean $respond)

Read entity by issue GET request



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean**



### listAction

    null Chayka\MVC\RestController::listAction(boolean $respond)

Action when get root requested.

Called to fetch list of entities

* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean** - &lt;p&gt;if true JSON wrapped entity will be responded&lt;/p&gt;



### indexAction

    null Chayka\MVC\RestController::indexAction(boolean $respond)

Alias of listAction - default action,
both can be redefined



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean**



### postAction

    null Chayka\MVC\RestController::postAction(boolean $respond)

Alias of createAction, both can be redefined



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean**



### getAction

    null Chayka\MVC\RestController::getAction(boolean $respond)

Alias of readAction, both can be redefined



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean**



### putAction

    null Chayka\MVC\RestController::putAction(boolean $respond)

Alias of updateAction, both can be redefined



* Visibility: **public**
* This method is defined by [Chayka\MVC\RestController](Chayka-MVC-RestController.md)


#### Arguments
* $respond **boolean**



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



### __construct

    mixed Chayka\MVC\Controller::__construct(\Chayka\MVC\Application $application)

Controller constructor



* Visibility: **public**
* This method is defined by [Chayka\MVC\Controller](Chayka-MVC-Controller.md)


#### Arguments
* $application **[Chayka\MVC\Application](Chayka-MVC-Application.md)**



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


