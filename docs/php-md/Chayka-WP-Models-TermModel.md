Chayka\WP\Models\TermModel
===============






* Class name: TermModel
* Namespace: Chayka\WP\Models
* This class implements: [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md), [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md), [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md), [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)




Properties
----------


### $validationErrors

    protected mixed $validationErrors





* Visibility: **protected**
* This property is **static**.


### $wpTerm

    protected mixed $wpTerm





* Visibility: **protected**


Methods
-------


### __construct

    mixed Chayka\WP\Models\TermModel::__construct()





* Visibility: **public**




### getDbIdColumn

    mixed Chayka\WP\Helpers\DbReady::getDbIdColumn()

Get id column name in db table



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)




### getDbTable

    string Chayka\WP\Helpers\DbReady::getDbTable()

Get db table name for the instance storage.



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)




### getId

    mixed Chayka\WP\Helpers\DbReady::getId()

Get instance id



* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)




### setId

    \Chayka\WP\Helpers\DbReady Chayka\WP\Helpers\DbReady::setId($id)

Set instance id



* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $id **mixed**



### getTermId

    integer Chayka\WP\Models\TermModel::getTermId()

Get term id



* Visibility: **public**




### setTermId

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setTermId($val)

Set term id



* Visibility: **public**


#### Arguments
* $val **mixed**



### getName

    string Chayka\WP\Models\TermModel::getName()

Get term name



* Visibility: **public**




### setName

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setName(string $val)

Set term name



* Visibility: **public**


#### Arguments
* $val **string**



### getSlug

    string Chayka\WP\Models\TermModel::getSlug()

Get term slug



* Visibility: **public**




### setSlug

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setSlug(string $val)

Set term slug



* Visibility: **public**


#### Arguments
* $val **string**



### getGroup

    integer Chayka\WP\Models\TermModel::getGroup()

Get term group



* Visibility: **public**




### setGroup

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setGroup(integer $val)

Set term group



* Visibility: **public**


#### Arguments
* $val **integer**



### getRelationId

    integer Chayka\WP\Models\TermModel::getRelationId()

Get term-to-post relation id (term_taxonomy_id)



* Visibility: **public**




### setRelationId

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setRelationId($val)

Set term-to-post relation id (term_taxonomy_id)



* Visibility: **public**


#### Arguments
* $val **mixed**



### getTaxonomy

    string Chayka\WP\Models\TermModel::getTaxonomy()

Get taxonomy



* Visibility: **public**




### setTaxonomy

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setTaxonomy(string $val)

Set taxonomy



* Visibility: **public**


#### Arguments
* $val **string**



### getDescription

    string Chayka\WP\Models\TermModel::getDescription()

Get term description



* Visibility: **public**




### setDescription

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setDescription(string $val)

Set term description



* Visibility: **public**


#### Arguments
* $val **string**



### getParentId

    integer Chayka\WP\Models\TermModel::getParentId()

Get parent term id



* Visibility: **public**




### setParentId

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setParentId($val)

Set parent term id



* Visibility: **public**


#### Arguments
* $val **mixed**



### getCountPerTaxonomy

    integer Chayka\WP\Models\TermModel::getCountPerTaxonomy()

Get number of term occurrences across the taxonomy



* Visibility: **public**




### setCountPerTaxonomy

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::setCountPerTaxonomy(integer $val)

Set number of term occurrences across the taxonomy



* Visibility: **public**


#### Arguments
* $val **integer**



### getHref

    string|\WP_Error Chayka\WP\Models\TermModel::getHref()

Get term href



* Visibility: **public**




### __get

    mixed Chayka\WP\Models\TermModel::__get($name)

Magic getter that allows to use TermModel where wpTerm should be used



* Visibility: **public**


#### Arguments
* $name **mixed**



### insert

    integer Chayka\WP\Helpers\DbReady::insert()

Insert current instance to db and return object id



* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)




### update

    integer Chayka\WP\Helpers\DbReady::update()

Update corresponding db row in db and return object id.



* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)




### delete

    boolean Chayka\WP\Helpers\DbReady::delete()

Delete corresponding db row from db.



* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)




### packDbRecord

    array Chayka\WP\Helpers\DbReady::packDbRecord(boolean $forUpdate)

Packs this instance for db insert/update



* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $forUpdate **boolean**



### unpackDbRecord

    \Chayka\WP\Helpers\DbReady Chayka\WP\Helpers\DbReady::unpackDbRecord(array|object $dbRecord)

Unpacks db result object into this instance



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $dbRecord **array|object**



### selectById

    mixed Chayka\WP\Helpers\DbReady::selectById($id, boolean $useCache)

Select instance from db by id.



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $id **mixed**
* $useCache **boolean**



### selectBy

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::selectBy(string $field, string $value, string $taxonomy, string $output, string $filter)

Select term by one of the following fields:
'slug', 'name', 'id' (term_id), or 'term_taxonomy_id'



* Visibility: **public**
* This method is **static**.


#### Arguments
* $field **string** - &lt;p&gt;Either &#039;slug&#039;, &#039;name&#039;, &#039;id&#039; (term_id), or &#039;term_taxonomy_id&#039;&lt;/p&gt;
* $value **string**
* $taxonomy **string**
* $output **string**
* $filter **string**



### selectByTermId

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::selectByTermId(integer $value, string $taxonomy, string $output, string $filter)

Select term by term id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **integer**
* $taxonomy **string**
* $output **string**
* $filter **string**



### selectBySlug

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::selectBySlug(string $value, string $taxonomy, string $output, string $filter)

Select term by slug



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **string**
* $taxonomy **string**
* $output **string**
* $filter **string**



### selectByName

    \Chayka\WP\Models\TermModel Chayka\WP\Models\TermModel::selectByName(string $value, string $taxonomy, string $output, string $filter)

Select term by name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **string**
* $taxonomy **string**
* $output **string**
* $filter **string**



### selectTerms

    \Chayka\WP\Models\array(TermModel) Chayka\WP\Models\TermModel::selectTerms(string|array $taxonomies, array|string $args)

Select term by filtering args.

Use TermModel::query() or TermModel::queryPostTerms() instead.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $taxonomies **string|array** - &lt;p&gt;Taxonomy name or list of Taxonomy names.&lt;/p&gt;
* $args **array|string**



### query

    \Chayka\WP\Queries\TermQuery Chayka\WP\Models\TermModel::query(string|\Chayka\WP\Models\array(string) $taxonomies)

Get query helper instance



* Visibility: **public**
* This method is **static**.


#### Arguments
* $taxonomies **string|Chayka\WP\Models\array(string)**



### queryPostTerms

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Models\TermModel::queryPostTerms(\Chayka\WP\Models\PostModel $post, string|\Chayka\WP\Models\array(string) $taxonomies)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $post **[Chayka\WP\Models\PostModel](Chayka-WP-Models-PostModel.md)**
* $taxonomies **string|Chayka\WP\Models\array(string)**



### getValidationErrors

    mixed Chayka\Helpers\InputReady::getValidationErrors()





* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md)




### addValidationErrors

    mixed Chayka\Helpers\InputReady::addValidationErrors($errors)





* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md)


#### Arguments
* $errors **mixed**



### unpackJsonItem

    \Chayka\Helpers\JsonReady Chayka\Helpers\JsonReady::unpackJsonItem($data)

Assigns inner values from the ones provided in $data



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md)


#### Arguments
* $data **mixed**



### validateInput

    mixed Chayka\Helpers\InputReady::validateInput($input, $oldState)





* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md)


#### Arguments
* $input **mixed**
* $oldState **mixed**



### packJsonItem

    \Chayka\Helpers\array($key=>$value); Chayka\Helpers\JsonReady::packJsonItem()

Returns assoc array to be packed into json payload



* Visibility: **public**
* This method is defined by [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md)




### userCan

    mixed Chayka\WP\Helpers\AclReady::userCan(string $privilege, \Chayka\WP\Models\UserModel|null $user)





* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)


#### Arguments
* $privilege **string**
* $user **[Chayka\WP\Models\UserModel](Chayka-WP-Models-UserModel.md)|null**


