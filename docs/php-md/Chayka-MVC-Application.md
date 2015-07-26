Chayka\MVC\Application
===============






* Class name: Application
* Namespace: Chayka\MVC





Properties
----------


### $router

    protected mixed $router





* Visibility: **protected**


### $controllers

    protected mixed $controllers





* Visibility: **protected**


### $path

    protected mixed $path





* Visibility: **protected**


### $id

    protected mixed $id





* Visibility: **protected**


Methods
-------


### __construct

    mixed Chayka\MVC\Application::__construct($appPath, string $appId)

Application constructor



* Visibility: **public**


#### Arguments
* $appPath **mixed**
* $appId **string**



### getId

    string Chayka\MVC\Application::getId()

Get application id



* Visibility: **public**




### getPath

    string Chayka\MVC\Application::getPath()

Get application path



* Visibility: **public**




### getRouter

    \Chayka\MVC\Router Chayka\MVC\Application::getRouter()

Get router to setup routing



* Visibility: **public**




### getController

    \Chayka\MVC\Controller Chayka\MVC\Application::getController(string $className, $newController)

Get new or cached controller for classname



* Visibility: **public**


#### Arguments
* $className **string**
* $newController **mixed**



### dispatch

    string Chayka\MVC\Application::dispatch(string|array $request, boolean $newController, \Chayka\MVC\View $forwardedView)

Dispatch requestUri (call the 'controller > action > view' chain)
Cached controller will be used if available.

Specify $newController = true if you need a clean one.

* Visibility: **public**


#### Arguments
* $request **string|array**
* $newController **boolean**
* $forwardedView **[Chayka\MVC\View](Chayka-MVC-View.md)**


