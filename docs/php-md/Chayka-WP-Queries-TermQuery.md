Chayka\WP\Queries\TermQuery
===============






* Class name: TermQuery
* Namespace: Chayka\WP\Queries





Properties
----------


### $vars

    protected mixed $vars = array()





* Visibility: **protected**


### $taxonomies

    protected mixed $taxonomies = null





* Visibility: **protected**


Methods
-------


### __construct

    mixed Chayka\WP\Queries\TermQuery::__construct(string|\Chayka\WP\Queries\array(string) $taxonomies)





* Visibility: **public**


#### Arguments
* $taxonomies **string|Chayka\WP\Queries\array(string)**



### getVars

    array Chayka\WP\Queries\TermQuery::getVars()

Get all vars



* Visibility: **public**




### setVars

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::setVars(array $vars)

Add vars to the set



* Visibility: **public**


#### Arguments
* $vars **array**



### setVar

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::setVar(string $key, mixed $value)

Set query filter var



* Visibility: **public**


#### Arguments
* $key **string**
* $value **mixed**



### query

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::query(string|\Chayka\WP\Queries\array(string) $taxonomies)

Create instance of query object



* Visibility: **public**
* This method is **static**.


#### Arguments
* $taxonomies **string|Chayka\WP\Queries\array(string)**



### select

    \Chayka\WP\Queries\array(TermModel) Chayka\WP\Queries\TermQuery::select(string|\Chayka\WP\Queries\array(string) $taxonomies)

Select all matching terms



* Visibility: **public**


#### Arguments
* $taxonomies **string|Chayka\WP\Queries\array(string)**



### selectOne

    \Chayka\WP\Models\TermModel Chayka\WP\Queries\TermQuery::selectOne(string|\Chayka\WP\Queries\array(string) $taxonomy)

Select first matching term



* Visibility: **public**


#### Arguments
* $taxonomy **string|Chayka\WP\Queries\array(string)**



### order

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::order(string $order)

Designates the ascending or descending order of the 'orderby' parameter.

Defaults to 'ASC'

* Visibility: **public**


#### Arguments
* $order **string**



### order_ASC

    mixed Chayka\WP\Queries\TermQuery::order_ASC()





* Visibility: **public**




### order_DESC

    mixed Chayka\WP\Queries\TermQuery::order_DESC()





* Visibility: **public**




### orderBy

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::orderBy(string $orderBy)

Sort retrieved users by parameter. Defaults to 'login'.



* Visibility: **public**


#### Arguments
* $orderBy **string**



### orderBy_ID

    mixed Chayka\WP\Queries\TermQuery::orderBy_ID()





* Visibility: **public**




### orderBy_Count

    mixed Chayka\WP\Queries\TermQuery::orderBy_Count()





* Visibility: **public**




### orderBy_Name

    mixed Chayka\WP\Queries\TermQuery::orderBy_Name()





* Visibility: **public**




### orderBy_Slug

    mixed Chayka\WP\Queries\TermQuery::orderBy_Slug()





* Visibility: **public**




### orderBy_TermGroup

    mixed Chayka\WP\Queries\TermQuery::orderBy_TermGroup()





* Visibility: **public**




### orderBy_None

    mixed Chayka\WP\Queries\TermQuery::orderBy_None()





* Visibility: **public**




### hideEmpty

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::hideEmpty(boolean $hide)

Whether to return empty $terms



* Visibility: **public**


#### Arguments
* $hide **boolean**



### showEmpty

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::showEmpty(boolean $show)

Whether to return empty $terms



* Visibility: **public**


#### Arguments
* $show **boolean**



### excludeIds

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::excludeIds(integer|string|array $termIds)

An array of term ids to exclude. Also accepts a string of comma-separated ids.



* Visibility: **public**


#### Arguments
* $termIds **integer|string|array**



### excludeTreeIds

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::excludeTreeIds(integer|string|array $parentTermIds)

An array of parent term ids to exclude



* Visibility: **public**


#### Arguments
* $parentTermIds **integer|string|array**



### includeIds

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::includeIds(integer|string|array $termIds)

An array of term ids to include. Empty returns all.



* Visibility: **public**


#### Arguments
* $termIds **integer|string|array**



### number

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::number(integer $number)

The maximum number of terms to return. Default is to return them all.



* Visibility: **public**


#### Arguments
* $number **integer**



### fields

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::fields(string|\Chayka\WP\Queries\array(string) $fields)

Set return values.



* Visibility: **public**


#### Arguments
* $fields **string|Chayka\WP\Queries\array(string)**



### fields_All

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::fields_All()

all - returns an array of term objects - Default



* Visibility: **public**




### fields_Ids

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::fields_Ids()

ids - returns an array of integers



* Visibility: **public**




### fields_Names

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::fields_Names()

names - returns an array of strings



* Visibility: **public**




### fields_Count

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::fields_Count()

count - (3.2+) returns the number of terms found



* Visibility: **public**




### fields_ID_ParentId

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::fields_ID_ParentId()

id=>parent - returns an associative array where
the key is the term id and
the value is the parent term id if present or 0



* Visibility: **public**




### slug

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::slug(string $slug)

Returns terms whose "slug" matches this value. Default is empty string.



* Visibility: **public**


#### Arguments
* $slug **string**



### parentId

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::parentId(integer $parentTermId)

Get direct children of this term (only terms whose explicit parent is this value).

If 0 is passed, only top-level terms are returned. Default is an empty string.

* Visibility: **public**


#### Arguments
* $parentTermId **integer**



### hierarchical

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::hierarchical(boolean $hierarchical)

Whether to include terms that have non-empty descendants
(even if 'hide_empty' is set to true).



* Visibility: **public**


#### Arguments
* $hierarchical **boolean**



### hierarchical_Yes

    mixed Chayka\WP\Queries\TermQuery::hierarchical_Yes()





* Visibility: **public**




### hierarchical_No

    mixed Chayka\WP\Queries\TermQuery::hierarchical_No()





* Visibility: **public**




### childOf

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::childOf(integer $parentTermId)

Get all descendants of this term. Default is 0.



* Visibility: **public**


#### Arguments
* $parentTermId **integer**



### get

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::get(string $value)

Default is nothing . Allow for overwriting 'hide_empty' and 'child_of',
which can be done by setting the value to 'all'.



* Visibility: **public**


#### Arguments
* $value **string**



### nameLike

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::nameLike(string $name)

The term name you wish to match. It does a LIKE 'term_name%' query.

This matches terms that begin with the

* Visibility: **public**


#### Arguments
* $name **string**



### padCounts

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::padCounts(boolean $count)

If true, count all of the children along with the $terms.



* Visibility: **public**


#### Arguments
* $count **boolean**



### offset

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::offset(integer $offset)

The number by which to offset the terms query.



* Visibility: **public**


#### Arguments
* $offset **integer**



### search

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::search(string $name)

The term name you wish to match. It does a LIKE '%term_name%' query.

This matches terms that contain the 'search'

* Visibility: **public**


#### Arguments
* $name **string**



### cacheDomain

    \Chayka\WP\Queries\TermQuery Chayka\WP\Queries\TermQuery::cacheDomain(string $domain)

Version 3.2 and above. The 'cache_domain' argument enables a unique cache key
to be produced when the query produced by get_terms() is stored in object cache.

For instance, if you are using one of this function's filters to modify the query
(such as 'terms_clauses'), setting 'cache_domain' to a unique value will not
overwrite the cache for similar queries. Default value is 'core'.

* Visibility: **public**


#### Arguments
* $domain **string**


