Chayka\WP\Queries\PostTermQuery
===============






* Class name: PostTermQuery
* Namespace: Chayka\WP\Queries





Properties
----------


### $vars

    protected mixed $vars = array()





* Visibility: **protected**


### $taxonomies

    protected mixed $taxonomies = null





* Visibility: **protected**


### $post

    protected mixed $post = null





* Visibility: **protected**


Methods
-------


### __construct

    mixed Chayka\WP\Queries\PostTermQuery::__construct($post, $taxonomies)





* Visibility: **public**


#### Arguments
* $post **mixed**
* $taxonomies **mixed**



### getVars

    array Chayka\WP\Queries\PostTermQuery::getVars()

Get all vars



* Visibility: **public**




### setVars

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::setVars(array $vars)

Add vars to the set



* Visibility: **public**


#### Arguments
* $vars **array**



### setVar

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::setVar(string $key, mixed $value)

Set query filter var



* Visibility: **public**


#### Arguments
* $key **string**
* $value **mixed**



### query

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::query(\Chayka\WP\Models\PostModel $post, string|\Chayka\WP\Queries\array(string) $taxonomies)

Create instance of query object



* Visibility: **public**
* This method is **static**.


#### Arguments
* $post **[Chayka\WP\Models\PostModel](Chayka-WP-Models-PostModel.md)**
* $taxonomies **string|Chayka\WP\Queries\array(string)**



### select

    \Chayka\WP\Queries\array(TermModel) Chayka\WP\Queries\PostTermQuery::select(\Chayka\WP\Models\PostModel $post, string|\Chayka\WP\Queries\array(string) $taxonomies)

Load terms into the post defined.

You can omit $post and $taxonomies if this params where provided for constructor.

* Visibility: **public**


#### Arguments
* $post **[Chayka\WP\Models\PostModel](Chayka-WP-Models-PostModel.md)**
* $taxonomies **string|Chayka\WP\Queries\array(string)**



### selectOne

    \Chayka\WP\Models\TermModel Chayka\WP\Queries\PostTermQuery::selectOne(string $taxonomy, \Chayka\WP\Models\PostModel $post)

Select first matching term for the taxonomy



* Visibility: **public**


#### Arguments
* $taxonomy **string**
* $post **[Chayka\WP\Models\PostModel](Chayka-WP-Models-PostModel.md)**



### order

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::order(string $order)

Designates the ascending or descending order of the 'orderby' parameter.

Defaults to 'ASC'

* Visibility: **public**


#### Arguments
* $order **string**



### order_ASC

    mixed Chayka\WP\Queries\PostTermQuery::order_ASC()





* Visibility: **public**




### order_DESC

    mixed Chayka\WP\Queries\PostTermQuery::order_DESC()





* Visibility: **public**




### orderBy

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::orderBy(string $orderBy)

Sort retrieved users by parameter. Defaults to 'login'.



* Visibility: **public**


#### Arguments
* $orderBy **string**



### orderBy_ID

    mixed Chayka\WP\Queries\PostTermQuery::orderBy_ID()





* Visibility: **public**




### orderBy_Count

    mixed Chayka\WP\Queries\PostTermQuery::orderBy_Count()





* Visibility: **public**




### orderBy_Name

    mixed Chayka\WP\Queries\PostTermQuery::orderBy_Name()





* Visibility: **public**




### orderBy_Slug

    mixed Chayka\WP\Queries\PostTermQuery::orderBy_Slug()





* Visibility: **public**




### orderBy_TermOrder

    mixed Chayka\WP\Queries\PostTermQuery::orderBy_TermOrder()





* Visibility: **public**




### orderBy_TermGroup

    mixed Chayka\WP\Queries\PostTermQuery::orderBy_TermGroup()





* Visibility: **public**




### orderBy_None

    mixed Chayka\WP\Queries\PostTermQuery::orderBy_None()





* Visibility: **public**




### fields

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::fields(string|\Chayka\WP\Queries\array(string) $fields)

Set return values.



* Visibility: **public**


#### Arguments
* $fields **string|Chayka\WP\Queries\array(string)**



### fields_All

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::fields_All()

all - returns an array of term objects - Default



* Visibility: **public**




### fields_AllWithObjectId

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::fields_AllWithObjectId()

all - returns an array of term objects - Default



* Visibility: **public**




### fields_Ids

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::fields_Ids()

ids - returns an array of integers



* Visibility: **public**




### fields_Names

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::fields_Names()

names - returns an array of strings



* Visibility: **public**




### fields_Slugs

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Queries\PostTermQuery::fields_Slugs()

slugs - returns an array of strings



* Visibility: **public**



