Chayka\WP\Models\UserModel
===============

Class implemented to handle user actions and manipulations
Used for authentification, registration, update, delete and userpics management




* Class name: UserModel
* Namespace: Chayka\WP\Models
* This class implements: [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md), [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md), [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md), [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)


Constants
----------


### SESSION_KEY

    const SESSION_KEY = '_user'





Properties
----------


### $userCacheById

    protected mixed $userCacheById = array()





* Visibility: **protected**
* This property is **static**.


### $userCacheByEmail

    protected mixed $userCacheByEmail = array()





* Visibility: **protected**
* This property is **static**.


### $userCacheByLogin

    protected mixed $userCacheByLogin = array()





* Visibility: **protected**
* This property is **static**.


### $jsonMetaFields

    protected mixed $jsonMetaFields = array()





* Visibility: **protected**
* This property is **static**.


### $currentUser

    protected mixed $currentUser





* Visibility: **protected**
* This property is **static**.


### $validationErrors

    protected mixed $validationErrors





* Visibility: **protected**
* This property is **static**.


### $id

    protected mixed $id





* Visibility: **protected**


### $login

    protected mixed $login





* Visibility: **protected**


### $password

    protected mixed $password





* Visibility: **protected**


### $nicename

    protected mixed $nicename





* Visibility: **protected**


### $url

    protected mixed $url





* Visibility: **protected**


### $displayName

    protected mixed $displayName





* Visibility: **protected**


### $firstName

    protected mixed $firstName





* Visibility: **protected**


### $lastName

    protected mixed $lastName





* Visibility: **protected**


### $description

    protected mixed $description





* Visibility: **protected**


### $richEditing

    protected mixed $richEditing





* Visibility: **protected**


### $role

    protected mixed $role





* Visibility: **protected**


### $capabilities

    protected mixed $capabilities





* Visibility: **protected**


### $email

    protected mixed $email





* Visibility: **protected**


### $registered

    protected mixed $registered





* Visibility: **protected**


### $jabber

    protected mixed $jabber





* Visibility: **protected**


### $aim

    protected mixed $aim





* Visibility: **protected**


### $yim

    protected mixed $yim





* Visibility: **protected**


### $wpUser

    protected mixed $wpUser





* Visibility: **protected**


Methods
-------


### __construct

    mixed Chayka\WP\Models\UserModel::__construct()

UserModel constructor



* Visibility: **public**




### init

    mixed Chayka\WP\Models\UserModel::init()

Initialization with guest data



* Visibility: **public**




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



### getLogin

    string Chayka\WP\Models\UserModel::getLogin()

Get user login



* Visibility: **public**




### setLogin

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setLogin($login)

Set user login



* Visibility: **public**


#### Arguments
* $login **mixed**



### getPassword

    string Chayka\WP\Models\UserModel::getPassword()

Get user password



* Visibility: **public**




### setPassword

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setPassword(string $password)

Set password



* Visibility: **public**


#### Arguments
* $password **string**



### getNicename

    string Chayka\WP\Models\UserModel::getNicename()

Get user nicename (slug)



* Visibility: **public**




### setNicename

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setNicename($nicename)

Set user nicename (slug)



* Visibility: **public**


#### Arguments
* $nicename **mixed**



### getUrl

    string Chayka\WP\Models\UserModel::getUrl()

Get user's site url.

Not the user's profile link.

* Visibility: **public**




### setUrl

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setUrl(string $url)

Set user's site url.

Not the user's profile link.

* Visibility: **public**


#### Arguments
* $url **string**



### getDisplayName

    string Chayka\WP\Models\UserModel::getDisplayName()

Get user display name



* Visibility: **public**




### setDisplayName

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setDisplayName(string $displayName)

Set user display name



* Visibility: **public**


#### Arguments
* $displayName **string**



### getFirstName

    string Chayka\WP\Models\UserModel::getFirstName()

Get first name



* Visibility: **public**




### setFirstName

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setFirstName(string $firstName)

Set first name



* Visibility: **public**


#### Arguments
* $firstName **string**



### getLastName

    string Chayka\WP\Models\UserModel::getLastName()

Get last name



* Visibility: **public**




### setLastName

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setLastName($lastName)

Set last name



* Visibility: **public**


#### Arguments
* $lastName **mixed**



### getDescription

    string Chayka\WP\Models\UserModel::getDescription()

Get user description



* Visibility: **public**




### setDescription

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setDescription(string $description)

Set user description



* Visibility: **public**


#### Arguments
* $description **string**



### getRichEditing

    mixed Chayka\WP\Models\UserModel::getRichEditing()

Get 'rich_editing'



* Visibility: **public**




### setRichEditing

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setRichEditing($richEditing)

Set 'rich_editing'



* Visibility: **public**


#### Arguments
* $richEditing **mixed**



### getCapabilities

    array Chayka\WP\Models\UserModel::getCapabilities()

Get set of user capabilities



* Visibility: **public**




### hasRole

    boolean Chayka\WP\Models\UserModel::hasRole(string $role)

Check if user has role



* Visibility: **public**


#### Arguments
* $role **string**



### hasCapability

    boolean Chayka\WP\Models\UserModel::hasCapability($capability)

Check if user has capability



* Visibility: **public**


#### Arguments
* $capability **mixed**



### getRole

    string Chayka\WP\Models\UserModel::getRole()

Get the best (most powerful) available role



* Visibility: **public**




### setRole

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setRole($role)

Set user role
TODO: check if it saves somehow



* Visibility: **public**


#### Arguments
* $role **mixed**



### getEmail

    string Chayka\WP\Models\UserModel::getEmail()

Get user email



* Visibility: **public**




### setEmail

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setEmail(string $email)

Set user model



* Visibility: **public**


#### Arguments
* $email **string**



### getRegistered

    \DateTime Chayka\WP\Models\UserModel::getRegistered()

Get user registration datetime



* Visibility: **public**




### setRegistered

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setRegistered(\DateTime $registered)

Set user registration datetime



* Visibility: **public**


#### Arguments
* $registered **DateTime**



### getJabber

    string Chayka\WP\Models\UserModel::getJabber()

Set jabebr



* Visibility: **public**




### setJabber

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setJabber(string $jabber)

Get jabber



* Visibility: **public**


#### Arguments
* $jabber **string**



### getAim

    string Chayka\WP\Models\UserModel::getAim()

Get aim



* Visibility: **public**




### setAim

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setAim(string $aim)

Set aim



* Visibility: **public**


#### Arguments
* $aim **string**



### getYim

    string Chayka\WP\Models\UserModel::getYim()

Get yim



* Visibility: **public**




### setYim

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setYim(string $yim)

Set yim



* Visibility: **public**


#### Arguments
* $yim **string**



### getProfileLink

    string Chayka\WP\Models\UserModel::getProfileLink()

Get user profile link



* Visibility: **public**




### getWpUser

    object|\WP_User Chayka\WP\Models\UserModel::getWpUser()

Get original WP_User model if one is stored



* Visibility: **public**




### setWpUser

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::setWpUser(object|\WP_User $wpUser)

Set original WP_User model



* Visibility: **public**


#### Arguments
* $wpUser **object|WP_User**



### __get

    mixed Chayka\WP\Models\UserModel::__get($name)

Magic getter that allows to use UserModel where wpUser should be used



* Visibility: **public**


#### Arguments
* $name **mixed**



### getUserMeta

    mixed Chayka\WP\Models\UserModel::getUserMeta(integer $userId, string $key, boolean $single)

Get user meta single key-value pair or all key-values



* Visibility: **public**
* This method is **static**.


#### Arguments
* $userId **integer** - &lt;p&gt;Comment ID.&lt;/p&gt;
* $key **string** - &lt;p&gt;Optional. The meta key to retrieve. By default, returns data for all keys.&lt;/p&gt;
* $single **boolean** - &lt;p&gt;Whether to return a single value.&lt;/p&gt;



### updateUserMeta

    boolean Chayka\WP\Models\UserModel::updateUserMeta(integer $userId, string $key, string $value, string $oldValue)

Update user meta value for the specified key in the DB



* Visibility: **public**
* This method is **static**.


#### Arguments
* $userId **integer**
* $key **string**
* $value **string**
* $oldValue **string**



### deleteUserMeta

    boolean Chayka\WP\Models\UserModel::deleteUserMeta(integer $userId, string $key, string $oldValue)

Remove metadata matching criteria from a user.

You can match based on the key, or key and value. Removing based on key and
value, will keep from removing duplicate metadata with the same key. It also
allows removing all metadata matching key, if needed.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $userId **integer**
* $key **string**
* $oldValue **string**



### getMeta

    mixed Chayka\WP\Models\UserModel::getMeta(string $key, boolean $single)

Get user meta single key-value pair or all key-values



* Visibility: **public**


#### Arguments
* $key **string** - &lt;p&gt;Optional. The meta key to retrieve. By default, returns data for all keys.&lt;/p&gt;
* $single **boolean** - &lt;p&gt;Whether to return a single value.&lt;/p&gt;



### updateMeta

    boolean Chayka\WP\Models\UserModel::updateMeta(string $key, string $value, string $oldValue)

Update user meta value for the specified key in the DB



* Visibility: **public**


#### Arguments
* $key **string**
* $value **string**
* $oldValue **string**



### deleteMeta

    mixed Chayka\WP\Models\UserModel::deleteMeta($key, string $oldValue)





* Visibility: **public**


#### Arguments
* $key **mixed**
* $oldValue **string**



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

    boolean Chayka\WP\Models\UserModel::deleteById(integer $userId, integer $reassignUserId)

Deletes user with the specified $userId from db table



* Visibility: **public**
* This method is **static**.


#### Arguments
* $userId **integer**
* $reassignUserId **integer**



### selectById

    mixed Chayka\WP\Helpers\DbReady::selectById($id, boolean $useCache)

Select instance from db by id.



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $id **mixed**
* $useCache **boolean**



### selectByLogin

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::selectByLogin(string $login, boolean $useCache)

Select user by login



* Visibility: **public**
* This method is **static**.


#### Arguments
* $login **string**
* $useCache **boolean**



### selectByEmail

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::selectByEmail($email, boolean $useCache)

Select user by email



* Visibility: **public**
* This method is **static**.


#### Arguments
* $email **mixed**
* $useCache **boolean**



### selectBySlug

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::selectBySlug($slug)

Select user by slug (nicename)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $slug **mixed**



### selectUsers

    array Chayka\WP\Models\UserModel::selectUsers($wpUserQueryArgs)

Select users by filtering args.

Use UserModel::query() helper instead.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $wpUserQueryArgs **mixed**



### query

    \Chayka\WP\Queries\UserQuery Chayka\WP\Models\UserModel::query()

Get query helper instance.



* Visibility: **public**
* This method is **static**.




### currentUser

    \Chayka\WP\Models\UserModel Chayka\WP\Models\UserModel::currentUser()

Get current user instance



* Visibility: **public**
* This method is **static**.




### setJsonMetaFields

    mixed Chayka\WP\Models\UserModel::setJsonMetaFields(\Chayka\WP\Models\array(string) $metaFields)

Set meta fields that should be populated to json



* Visibility: **public**
* This method is **static**.


#### Arguments
* $metaFields **Chayka\WP\Models\array(string)**



### addJsonMetaField

    mixed Chayka\WP\Models\UserModel::addJsonMetaField(string $fieldName)

Add meta field name that should be populated to json



* Visibility: **public**
* This method is **static**.


#### Arguments
* $fieldName **string**



### removeJsonMetaField

    mixed Chayka\WP\Models\UserModel::removeJsonMetaField(string $fieldName)

Remove meta field name that should not be populated to json



* Visibility: **public**
* This method is **static**.


#### Arguments
* $fieldName **string**



### packJsonItem

    \Chayka\Helpers\array($key=>$value); Chayka\Helpers\JsonReady::packJsonItem()

Returns assoc array to be packed into json payload



* Visibility: **public**
* This method is defined by [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md)




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



### isAdmin

    boolean Chayka\WP\Models\UserModel::isAdmin()

TODO: revise this function
returns true if the user is administrator



* Visibility: **public**




### flushCache

    mixed Chayka\WP\Models\UserModel::flushCache()

Flush user cache



* Visibility: **public**
* This method is **static**.




### getUserCacheById

    mixed|null Chayka\WP\Models\UserModel::getUserCacheById(integer $id)

Get cached user by id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **integer**



### getUserCacheByEmail

    array Chayka\WP\Models\UserModel::getUserCacheByEmail(string $email)

Get cached user by email



* Visibility: **public**
* This method is **static**.


#### Arguments
* $email **string**



### getUserCacheByLogin

    array Chayka\WP\Models\UserModel::getUserCacheByLogin(string $login)

Get cached user by email



* Visibility: **public**
* This method is **static**.


#### Arguments
* $login **string**



### userCan

    mixed Chayka\WP\Helpers\AclReady::userCan(string $privilege, \Chayka\WP\Models\UserModel|null $user)





* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)


#### Arguments
* $privilege **string**
* $user **[Chayka\WP\Models\UserModel](Chayka-WP-Models-UserModel.md)|null**


