Chayka\MVC\ApplicationDispatcher
===============






* Class name: ApplicationDispatcher
* Namespace: Chayka\MVC





Properties
----------


### $applications

    protected mixed $applications = array()





* Visibility: **protected**
* This property is **static**.


### $routes

    protected mixed $routes = array()





* Visibility: **protected**
* This property is **static**.


### $forbiddenRoutes

    protected mixed $forbiddenRoutes = array()





* Visibility: **protected**
* This property is **static**.


### $notFound

    protected mixed $notFound = false





* Visibility: **protected**
* This property is **static**.


### $isMainPage

    protected mixed $isMainPage = false





* Visibility: **protected**
* This property is **static**.


Methods
-------


### registerApplication

    mixed Chayka\MVC\ApplicationDispatcher::registerApplication(\Chayka\MVC\Application $app, \Chayka\MVC\array(string) $routes)

Register MVC Application that will serve requests



* Visibility: **public**
* This method is **static**.


#### Arguments
* $app **[Chayka\MVC\Application](Chayka-MVC-Application.md)**
* $routes **Chayka\MVC\array(string)**



### forbidRoute

    mixed Chayka\MVC\ApplicationDispatcher::forbidRoute(string $mask, string $maskId)

Forbid route by preg mask



* Visibility: **public**
* This method is **static**.


#### Arguments
* $mask **string**
* $maskId **string**



### forbidRoutes

    mixed Chayka\MVC\ApplicationDispatcher::forbidRoutes(\Chayka\MVC\array(string) $routes)

Forbid several routes by preg masks



* Visibility: **public**
* This method is **static**.


#### Arguments
* $routes **Chayka\MVC\array(string)**



### isForbiddenRoute

    boolean Chayka\MVC\ApplicationDispatcher::isForbiddenRoute($requestUri)

Check request uri if it is forbidden



* Visibility: **public**
* This method is **static**.


#### Arguments
* $requestUri **mixed**



### canProcess

    integer Chayka\MVC\ApplicationDispatcher::canProcess($requestUri)

Check if uri can be processed



* Visibility: **public**
* This method is **static**.


#### Arguments
* $requestUri **mixed**



### dispatch

    null Chayka\MVC\ApplicationDispatcher::dispatch(null $uri, null $appId)

Dispatch $uri and return rendered response.

If no route found or route is forbidden returns null.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $uri **null**
* $appId **null**


