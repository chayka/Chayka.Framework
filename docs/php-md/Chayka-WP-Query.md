Chayka\WP\Query
===============






* Class name: Query
* Namespace: Chayka\WP
* Parent class: WP_Query





Properties
----------


### $options

    protected mixed $options = array()





* Visibility: **protected**
* This property is **static**.


### $_post

    protected mixed $_post = null





* Visibility: **protected**
* This property is **static**.


### $template

    protected mixed $template = null





* Visibility: **protected**
* This property is **static**.


Methods
-------


### parseRequest

    mixed Chayka\WP\Query::parseRequest()

This function is called on parse_request hook.

If it detects url that can be processed by any registered application it replaces
$wp_the_query with this modified WP_Query extended instance.
On get_posts it will return modified $post with MVC Application rendered content.

* Visibility: **public**
* This method is **static**.




### copyFrom

    mixed Chayka\WP\Query::copyFrom(\WP_Query $wp_query)

Get all the data from provided query.



* Visibility: **public**


#### Arguments
* $wp_query **WP_Query**



### setPost

    \Chayka\WP\Models\PostModel Chayka\WP\Query::setPost(\Chayka\WP\Models\PostModel|\WP_Post $post)

Set post data that will be returned by get_posts().

'post_content' will be replaced by MVC Application response.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $post **[Chayka\WP\Models\PostModel](Chayka-WP-Models-PostModel.md)|WP_Post**



### getPost

    \Chayka\WP\Models\PostModel Chayka\WP\Query::getPost()





* Visibility: **public**
* This method is **static**.




### getTemplate

    null|string Chayka\WP\Query::getTemplate()





* Visibility: **public**
* This method is **static**.




### setTemplate

    mixed Chayka\WP\Query::setTemplate(null|string $template)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $template **null|string**



### getProperty

    mixed Chayka\WP\Query::getProperty($key, $default)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $default **mixed**



### setProperty

    mixed Chayka\WP\Query::setProperty($key, $value)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $value **mixed**



### getIsHome

    mixed Chayka\WP\Query::getIsHome()





* Visibility: **public**
* This method is **static**.




### setIsHome

    mixed Chayka\WP\Query::setIsHome($is)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $is **mixed**



### getIs404

    mixed Chayka\WP\Query::getIs404()





* Visibility: **public**
* This method is **static**.




### setIs404

    mixed Chayka\WP\Query::setIs404($notFound)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $notFound **mixed**



### get_posts

    mixed Chayka\WP\Query::get_posts()





* Visibility: **public**




### renderResponse

    mixed Chayka\WP\Query::renderResponse($template)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $template **mixed**


