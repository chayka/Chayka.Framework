Chayka\WP\Models\ReadyModel
===============






* Class name: ReadyModel
* Namespace: Chayka\WP\Models
* This is an **abstract** class
* This class implements: [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md), [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md), [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md), [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)




Properties
----------


### $validationErrors

    protected mixed $validationErrors = array()





* Visibility: **protected**
* This property is **static**.


### $id

    protected mixed $id





* Visibility: **protected**


Methods
-------


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




### deleteById

    mixed Chayka\WP\Models\ReadyModel::deleteById($id)

Delete instance from db by id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### deleteBy

    mixed Chayka\WP\Models\ReadyModel::deleteBy(string $key, mixed $value)

Delete instance from db by some key



* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **string**
* $value **mixed**



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

    array|\Chayka\WP\Helpers\DbReady|null Chayka\WP\Models\ReadyModel::selectBy($key, $value, boolean $multiple, string $format)

Select instance from db by some key.

Mind to ensure index on $key field.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $value **mixed**
* $multiple **boolean**
* $format **string**



### selectSql

    array Chayka\WP\Models\ReadyModel::selectSql($sql)

Select data using sql query.

You can use {table} placeholder, that will be replaced with self::getDbTable().
Accepts slq-prepare format (sql with placeholders and optional params as values)

* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### selectAll

    array Chayka\WP\Models\ReadyModel::selectAll()

Select all entities



* Visibility: **public**
* This method is **static**.




### selectLimitOffset

    array Chayka\WP\Models\ReadyModel::selectLimitOffset(integer $limit, integer $offset)

Limited sql select.

Adds LIMIT $limit OFFSET $offset to $sql.

http://habrahabr.ru/post/217521/ -> join optimization

* Visibility: **public**
* This method is **static**.


#### Arguments
* $limit **integer**
* $offset **integer**



### selectPage

    array Chayka\WP\Models\ReadyModel::selectPage(integer $page, integer $perPage)

Limited sql select.

Adds LIMIT $perPage OFFSET ($page - 1) * $perPage to $sql.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $page **integer**
* $perPage **integer**



### getDbIdColumn

    mixed Chayka\WP\Helpers\DbReady::getDbIdColumn()

Get id column name in db table



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



### validateInput

    mixed Chayka\Helpers\InputReady::validateInput($input, $oldState)





* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md)


#### Arguments
* $input **mixed**
* $oldState **mixed**



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



### userCan

    mixed Chayka\WP\Helpers\AclReady::userCan(string $privilege, \Chayka\WP\Models\UserModel|null $user)





* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)


#### Arguments
* $privilege **string**
* $user **[Chayka\WP\Models\UserModel](Chayka-WP-Models-UserModel.md)|null**



### getDbTable

    string Chayka\WP\Helpers\DbReady::getDbTable()

Get db table name for the instance storage.



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)




### unpackDbRecord

    \Chayka\WP\Helpers\DbReady Chayka\WP\Helpers\DbReady::unpackDbRecord(array|object $dbRecord)

Unpacks db result object into this instance



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $dbRecord **array|object**



### packDbRecord

    array Chayka\WP\Helpers\DbReady::packDbRecord(boolean $forUpdate)

Packs this instance for db insert/update



* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $forUpdate **boolean**



### packJsonItem

    \Chayka\Helpers\array($key=>$value); Chayka\Helpers\JsonReady::packJsonItem()

Returns assoc array to be packed into json payload



* Visibility: **public**
* This method is defined by [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md)




### unpackJsonItem

    \Chayka\Helpers\JsonReady Chayka\Helpers\JsonReady::unpackJsonItem($data)

Assigns inner values from the ones provided in $data



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md)


#### Arguments
* $data **mixed**


