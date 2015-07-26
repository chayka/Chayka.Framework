Chayka\WP\Models\PostModel
===============






* Class name: PostModel
* Namespace: Chayka\WP\Models
* This class implements: [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md), [Chayka\Helpers\JsonReady](Chayka-Helpers-JsonReady.md), [Chayka\Helpers\InputReady](Chayka-Helpers-InputReady.md), [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)




Properties
----------


### $wpQuery

    public mixed $wpQuery





* Visibility: **public**
* This property is **static**.


### $postsFound

    public mixed $postsFound





* Visibility: **public**
* This property is **static**.


### $validationErrors

    protected mixed $validationErrors = array()





* Visibility: **protected**
* This property is **static**.


### $id

    protected mixed $id





* Visibility: **protected**


### $userId

    protected mixed $userId





* Visibility: **protected**


### $parentId

    protected mixed $parentId





* Visibility: **protected**


### $guid

    protected mixed $guid





* Visibility: **protected**


### $type

    protected mixed $type





* Visibility: **protected**


### $slug

    protected mixed $slug





* Visibility: **protected**


### $title

    protected mixed $title





* Visibility: **protected**


### $content

    protected mixed $content





* Visibility: **protected**


### $contentFiltered

    protected mixed $contentFiltered





* Visibility: **protected**


### $excerpt

    protected mixed $excerpt





* Visibility: **protected**


### $status

    protected mixed $status





* Visibility: **protected**


### $pingStatus

    protected mixed $pingStatus





* Visibility: **protected**


### $password

    protected mixed $password





* Visibility: **protected**


### $toPing

    protected mixed $toPing





* Visibility: **protected**


### $pinged

    protected mixed $pinged





* Visibility: **protected**


### $menuOrder

    protected mixed $menuOrder





* Visibility: **protected**


### $mimeType

    protected mixed $mimeType





* Visibility: **protected**


### $commentStatus

    protected mixed $commentStatus





* Visibility: **protected**


### $commentCount

    protected mixed $commentCount





* Visibility: **protected**


### $comments

    protected mixed $comments





* Visibility: **protected**


### $reviewsCount

    protected mixed $reviewsCount





* Visibility: **protected**


### $terms

    protected mixed $terms





* Visibility: **protected**


### $meta

    protected mixed $meta





* Visibility: **protected**


### $imageData

    protected mixed $imageData





* Visibility: **protected**


### $thumbnailId

    protected mixed $thumbnailId





* Visibility: **protected**


### $dtCreated

    protected mixed $dtCreated





* Visibility: **protected**


### $dtCreatedGMT

    protected mixed $dtCreatedGMT





* Visibility: **protected**


### $dtModified

    protected mixed $dtModified





* Visibility: **protected**


### $dtModifiedGMT

    protected mixed $dtModifiedGMT





* Visibility: **protected**


### $wpPost

    protected mixed $wpPost





* Visibility: **protected**


### $postsCacheById

    protected mixed $postsCacheById = array()





* Visibility: **protected**
* This property is **static**.


### $postsCacheBySlug

    protected mixed $postsCacheBySlug = array()





* Visibility: **protected**
* This property is **static**.


### $jsonMetaFields

    protected mixed $jsonMetaFields = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed Chayka\WP\Models\PostModel::__construct()

PostModel constructor



* Visibility: **public**




### init

    mixed Chayka\WP\Models\PostModel::init()





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



### getUserId

    integer Chayka\WP\Models\PostModel::getUserId()

Get author user id



* Visibility: **public**




### setUserId

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setUserId(integer $userId)

Set author user id



* Visibility: **public**


#### Arguments
* $userId **integer**



### getParentId

    integer Chayka\WP\Models\PostModel::getParentId()

Get parent-post id



* Visibility: **public**




### setParentId

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setParentId(integer $parentId)

Set parent-post id



* Visibility: **public**


#### Arguments
* $parentId **integer**



### getGuid

    string Chayka\WP\Models\PostModel::getGuid()

Get post guid



* Visibility: **public**




### setGuid

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setGuid(string $guid)

Set post guid



* Visibility: **public**


#### Arguments
* $guid **string**



### getType

    string Chayka\WP\Models\PostModel::getType()

Get post type



* Visibility: **public**




### setType

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setType(string $type)

Set post type



* Visibility: **public**


#### Arguments
* $type **string**



### getSlug

    string Chayka\WP\Models\PostModel::getSlug()

Get post name (slug)



* Visibility: **public**




### setSlug

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setSlug(string $slug)

Set post name (slug)



* Visibility: **public**


#### Arguments
* $slug **string**



### getTitle

    string Chayka\WP\Models\PostModel::getTitle()

Get post title



* Visibility: **public**




### setTitle

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setTitle(string $title)

Set post title



* Visibility: **public**


#### Arguments
* $title **string**



### getContent

    string Chayka\WP\Models\PostModel::getContent(boolean $wpautop)

Get post content



* Visibility: **public**


#### Arguments
* $wpautop **boolean** - &lt;p&gt;Set to true if you need auto-&lt;p&gt;&lt;/p&gt; (default: true)&lt;/p&gt;



### setContent

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setContent(string $content)

Set content



* Visibility: **public**


#### Arguments
* $content **string**



### getContentFiltered

    mixed Chayka\WP\Models\PostModel::getContentFiltered()





* Visibility: **public**




### setContentFiltered

    mixed Chayka\WP\Models\PostModel::setContentFiltered($contentFiltered)





* Visibility: **public**


#### Arguments
* $contentFiltered **mixed**



### getExcerpt

    string Chayka\WP\Models\PostModel::getExcerpt(boolean $generate, boolean $stripShortcodes)

Get post excerpt that was set or generated one



* Visibility: **public**


#### Arguments
* $generate **boolean** - &lt;p&gt;set to true if you need excerpt autogeneration&lt;/p&gt;
* $stripShortcodes **boolean** - &lt;p&gt;set to true will strip shortcodes while generating excerpt&lt;/p&gt;



### setExcerpt

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setExcerpt(string $excerpt)

Set post excerpt



* Visibility: **public**


#### Arguments
* $excerpt **string**



### getStatus

    string Chayka\WP\Models\PostModel::getStatus()

Get post status



* Visibility: **public**




### setStatus

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setStatus(string $status)

Set post status (publish|draft|deleted|future)



* Visibility: **public**


#### Arguments
* $status **string**



### getPingStatus

    string Chayka\WP\Models\PostModel::getPingStatus()

Get post ping status



* Visibility: **public**




### setPingStatus

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setPingStatus(string $pingStatus)

Set ping status (closed|open)



* Visibility: **public**


#### Arguments
* $pingStatus **string**



### getPassword

    string Chayka\WP\Models\PostModel::getPassword()

Get post password



* Visibility: **public**




### setPassword

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setPassword(string $password)

Set post password



* Visibility: **public**


#### Arguments
* $password **string**



### getToPing

    string Chayka\WP\Models\PostModel::getToPing()





* Visibility: **public**




### setToPing

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setToPing(string $toPing)





* Visibility: **public**


#### Arguments
* $toPing **string**



### getPinged

    string Chayka\WP\Models\PostModel::getPinged()





* Visibility: **public**




### setPinged

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setPinged(string $pinged)





* Visibility: **public**


#### Arguments
* $pinged **string**



### getMenuOrder

    integer Chayka\WP\Models\PostModel::getMenuOrder()

Get post order mark



* Visibility: **public**




### setMenuOrder

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setMenuOrder(integer $menuOrder)

Set post order mark



* Visibility: **public**


#### Arguments
* $menuOrder **integer**



### getMimeType

    string Chayka\WP\Models\PostModel::getMimeType()

Get attachment mime type



* Visibility: **public**




### setMimeType

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setMimeType(string $mimeType)

Set attachment mime type



* Visibility: **public**


#### Arguments
* $mimeType **string**



### isAttachmentImage

    boolean Chayka\WP\Models\PostModel::isAttachmentImage()

Check if post is attachment image



* Visibility: **public**




### getCommentStatus

    string Chayka\WP\Models\PostModel::getCommentStatus()

Get comment status



* Visibility: **public**




### setCommentStatus

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setCommentStatus(string $commentStatus)

Set comment status  (open|closed)



* Visibility: **public**


#### Arguments
* $commentStatus **string**



### getCommentCount

    integer Chayka\WP\Models\PostModel::getCommentCount()

Get comment count



* Visibility: **public**




### setCommentCount

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setCommentCount(integer $commentCount)

Set comment count



* Visibility: **public**


#### Arguments
* $commentCount **integer**



### getDtCreated

    \DateTime Chayka\WP\Models\PostModel::getDtCreated()

Get post creation datetime



* Visibility: **public**




### setDtCreated

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setDtCreated(\DateTime $dtCreated)

Set date creation datetime



* Visibility: **public**


#### Arguments
* $dtCreated **DateTime**



### getDtCreatedGMT

    \DateTime Chayka\WP\Models\PostModel::getDtCreatedGMT()

Get post creation datetime (GMT)



* Visibility: **public**




### getDtModified

    \DateTime Chayka\WP\Models\PostModel::getDtModified()

Get post modification datetime



* Visibility: **public**




### setDtModified

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setDtModified(\DateTime $dtModified)

Set post modification datetime



* Visibility: **public**


#### Arguments
* $dtModified **DateTime**



### getDtModifiedGMT

    \DateTime Chayka\WP\Models\PostModel::getDtModifiedGMT()

Get post modification datetime (GMT)



* Visibility: **public**




### getReviewsCount

    integer Chayka\WP\Models\PostModel::getReviewsCount()

Get count of page reviews.

Should be used in couple with incReviewsCount()

* Visibility: **public**




### setReviewsCount

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setReviewsCount(integer $value)

Set post reviews count. Used for model only, no database modification made.

Use incReviewsCount() instead.

* Visibility: **public**


#### Arguments
* $value **integer**



### incReviewsCount

    integer Chayka\WP\Models\PostModel::incReviewsCount()

Increases post reviews count by one.

Should be called in PostController::viewAction() for example.

* Visibility: **public**




### isVisited

    boolean Chayka\WP\Models\PostModel::isVisited()

Checks if post has been already visited today.

Works in couple with incReviewsCount() only

* Visibility: **public**




### getWpPost

    \WP_Post Chayka\WP\Models\PostModel::getWpPost()

Get original WP_Post object if the one is preserved



* Visibility: **public**




### setWpPost

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setWpPost(\WP_Post|object $wpPost)

Set original WP_Post object to be preserved



* Visibility: **public**


#### Arguments
* $wpPost **WP_Post|object**



### __get

    mixed Chayka\WP\Models\PostModel::__get($name)

Magic getter that allows to use PostModel where wpPost should be used



* Visibility: **public**


#### Arguments
* $name **mixed**



### getHref

    string Chayka\WP\Models\PostModel::getHref()

Get post href. Utilizes get_permalink().



* Visibility: **public**




### getHrefNext

    string Chayka\WP\Models\PostModel::getHrefNext(boolean $in_same_cat)

Get href to the next WP post



* Visibility: **public**


#### Arguments
* $in_same_cat **boolean**



### getHrefPrev

    string Chayka\WP\Models\PostModel::getHrefPrev(boolean $in_same_cat)

Get href to the previous WP post



* Visibility: **public**


#### Arguments
* $in_same_cat **boolean**



### getHrefEdit

    string Chayka\WP\Models\PostModel::getHrefEdit(boolean $checkPermissions, string $context)

Get post edit link



* Visibility: **public**


#### Arguments
* $checkPermissions **boolean**
* $context **string**



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

    mixed Chayka\WP\Models\PostModel::deleteById(integer $postId, boolean $forceDelete)

Deletes post with the specified $post from db table



* Visibility: **public**
* This method is **static**.


#### Arguments
* $postId **integer**
* $forceDelete **boolean** - &lt;p&gt;Whether to bypass trash and force deletion. Defaults to false.&lt;/p&gt;



### selectById

    mixed Chayka\WP\Helpers\DbReady::selectById($id, boolean $useCache)

Select instance from db by id.



* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\WP\Helpers\DbReady](Chayka-WP-Helpers-DbReady.md)


#### Arguments
* $id **mixed**
* $useCache **boolean**



### selectBySlug

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::selectBySlug(string $slug, string $postType, boolean $useCache, boolean $isPreview)

Select model from DB by slug



* Visibility: **public**
* This method is **static**.


#### Arguments
* $slug **string**
* $postType **string**
* $useCache **boolean**
* $isPreview **boolean**



### selectByTitle

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::selectByTitle(string $title, string $postType)

Selects post of specified post type by title.

The use of this function is not recommended as WP

* Visibility: **public**
* This method is **static**.


#### Arguments
* $title **string**
* $postType **string**



### query

    \Chayka\WP\Queries\PostQuery Chayka\WP\Models\PostModel::query(boolean $globalImport)

Get PostQuery object to create a query.

Call ->select() to fetch queried models;
The count of found rows can be found by calling postsFound() aftermath.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $globalImport **boolean** - &lt;p&gt;set to true if you need import from $wp_query&lt;/p&gt;



### selectPosts

    \Chayka\WP\Models\array(PostModel) Chayka\WP\Models\PostModel::selectPosts(array $wpPostsQueryArgs)

Select models using WP_Query syntax.

The count of found rows can be found by calling postsFound() aftermath.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $wpPostsQueryArgs **array**



### selectSql

    \Chayka\WP\Models\array(PostModel) Chayka\WP\Models\PostModel::selectSql(string $sql)

Select models using SQL query.

Should start with 'SELECT * FROM {$wpdb->posts}'
The count of found rows can be found by calling postsFound() aftermath.

* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **string**



### getWpQuery

    \WP_Query Chayka\WP\Models\PostModel::getWpQuery()

Get associated $wp_query if set



* Visibility: **public**
* This method is **static**.




### postsFound

    integer Chayka\WP\Models\PostModel::postsFound()

Get number of posts found using last mass fetch from DB



* Visibility: **public**
* This method is **static**.




### getPostMeta

    mixed Chayka\WP\Models\PostModel::getPostMeta(integer $postId, string $key, boolean $single)

Get post meta single key-value pair or all key-values



* Visibility: **public**
* This method is **static**.


#### Arguments
* $postId **integer** - &lt;p&gt;Post ID.&lt;/p&gt;
* $key **string** - &lt;p&gt;Optional. The meta key to retrieve. By default, returns data for all keys.&lt;/p&gt;
* $single **boolean** - &lt;p&gt;Whether to return a single value.&lt;/p&gt;



### updatePostMeta

    boolean Chayka\WP\Models\PostModel::updatePostMeta(integer $postId, string $key, string $value, string $oldValue)

Update post meta value for the specified key in the DB



* Visibility: **public**
* This method is **static**.


#### Arguments
* $postId **integer**
* $key **string**
* $value **string**
* $oldValue **string**



### deletePostMeta

    boolean Chayka\WP\Models\PostModel::deletePostMeta(integer $postId, string $key, mixed $value)

Delete post meta value



* Visibility: **public**
* This method is **static**.


#### Arguments
* $postId **integer**
* $key **string**
* $value **mixed**



### getMeta

    mixed Chayka\WP\Models\PostModel::getMeta(string $key, boolean $single)

Get post meta single key-value pair or all key-values



* Visibility: **public**


#### Arguments
* $key **string** - &lt;p&gt;Optional. The meta key to retrieve. By default, returns data for all keys.&lt;/p&gt;
* $single **boolean** - &lt;p&gt;Whether to return a single value.&lt;/p&gt;



### updateOrDeleteMeta

    boolean Chayka\WP\Models\PostModel::updateOrDeleteMeta(string $key, string $value, string $oldValue)

Update post meta value for the specified key in the DB
If value is empty then delete it



* Visibility: **public**


#### Arguments
* $key **string**
* $value **string**
* $oldValue **string**



### updateMeta

    boolean Chayka\WP\Models\PostModel::updateMeta(string $key, string $value, string $oldValue)

Update post meta value for the specified key in the DB



* Visibility: **public**


#### Arguments
* $key **string**
* $value **string**
* $oldValue **string**



### deleteMeta

    boolean Chayka\WP\Models\PostModel::deleteMeta(string $key, mixed $value)

Delete post meta value



* Visibility: **public**


#### Arguments
* $key **string**
* $value **mixed**



### getTerms

    \Chayka\WP\Models\array(string|\Chayka\WP\Models\TermModel) Chayka\WP\Models\PostModel::getTerms(string|array $taxonomy)

Get post terms. Should be set first by setTerms() or load by loadTerms() or queryTerms()
If taxonomy not set returns



* Visibility: **public**


#### Arguments
* $taxonomy **string|array**



### setTerms

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setTerms(\Chayka\WP\Models\array(string|\Chayka\WP\Models\WP_Term|\Chayka\WP\Models\TermModel) $terms, string $taxonomy)

Set post terms



* Visibility: **public**


#### Arguments
* $terms **Chayka\WP\Models\array(string|Chayka\WP\Models\WP_Term|Chayka\WP\Models\TermModel)**
* $taxonomy **string** - &lt;p&gt;taxonomy&lt;/p&gt;



### selectTerms

    \Chayka\WP\Models\array(TermModel) Chayka\WP\Models\PostModel::selectTerms(integer $postId, string|\Chayka\WP\Models\array(string) $taxonomy, array|\Chayka\WP\Queries\TermQuery $args)

Select terms for the specified postId and taxonomy



* Visibility: **public**
* This method is **static**.


#### Arguments
* $postId **integer**
* $taxonomy **string|Chayka\WP\Models\array(string)**
* $args **array|[array](Chayka-WP-Queries-TermQuery.md)**



### loadTerms

    \Chayka\WP\Models\array(TermModel) Chayka\WP\Models\PostModel::loadTerms(string|\Chayka\WP\Models\array(string) $taxonomies, array|\Chayka\WP\Queries\TermQuery $args)

Load terms for this post and taxonomy.

Utilizes selectTerms

* Visibility: **public**


#### Arguments
* $taxonomies **string|Chayka\WP\Models\array(string)**
* $args **array|[array](Chayka-WP-Queries-TermQuery.md)**



### updateTerms

    mixed Chayka\WP\Models\PostModel::updateTerms(\Chayka\WP\Models\array(string|integer|\Chayka\WP\Models\WP_Term|\Chayka\WP\Models\TermModel) $terms, string $taxonomy, boolean $append)

Update set of post's terms in DB



* Visibility: **public**


#### Arguments
* $terms **Chayka\WP\Models\array(string|integer|Chayka\WP\Models\WP_Term|Chayka\WP\Models\TermModel)** - &lt;p&gt;if omitted $this-&gt;getTerms($taxonomy) is taken&lt;/p&gt;
* $taxonomy **string** - &lt;p&gt;if omitted $terms should be like array(&#039;post_tag&#039; =&gt; ... , &#039;category&#039; =&gt; ... )&lt;/p&gt;
* $append **boolean** - &lt;p&gt;append or replace&lt;/p&gt;



### queryTerms

    \Chayka\WP\Queries\PostTermQuery Chayka\WP\Models\PostModel::queryTerms(string|\Chayka\WP\Models\array(string) $taxonomies)

Get PostTermQuery object to query post terms.

Call ->select() at the end to load terms into this post

* Visibility: **public**


#### Arguments
* $taxonomies **string|Chayka\WP\Models\array(string)**



### getTaxonomies

    \Chayka\WP\Models\array(string) Chayka\WP\Models\PostModel::getTaxonomies()

Get taxonomy identifiers associated with this post type



* Visibility: **public**




### getComments

    \Chayka\WP\Models\array(CommentModel) Chayka\WP\Models\PostModel::getComments()

Get post comments. Should set first by setComments() or load by loadComments() or queryComments()



* Visibility: **public**




### setComments

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setComments(\Chayka\WP\Models\array(CommentModel) $comments)

Set post comments



* Visibility: **public**


#### Arguments
* $comments **Chayka\WP\Models\array(CommentModel)**



### loadComments

    integer Chayka\WP\Models\PostModel::loadComments(array $args)

Load post comments into the post object



* Visibility: **public**


#### Arguments
* $args **array** - &lt;p&gt;WP_Comment_Query args&lt;/p&gt;



### queryComments

    \Chayka\WP\Queries\CommentQuery Chayka\WP\Models\PostModel::queryComments()

Get CommentQuery object to query this post comments.

Call ->select() at the end to load comments into this model.

* Visibility: **public**




### getAttachments

    mixed Chayka\WP\Models\PostModel::getAttachments($type)





* Visibility: **public**


#### Arguments
* $type **mixed**



### getAttachmentUrl

    string Chayka\WP\Models\PostModel::getAttachmentUrl()

Get attachment url



* Visibility: **public**




### getImageData

    mixed Chayka\WP\Models\PostModel::getImageData()

Get image data in case this post is an attachment image.

Should be set by setImageData or loaded by loadImageData().
loadImageData can be used instead

* Visibility: **public**




### setImageData

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::setImageData(array $imageData)

Set image data in case this post is an attachment image.

Use within the model only.

* Visibility: **public**


#### Arguments
* $imageData **array**



### loadImageData

    array Chayka\WP\Models\PostModel::loadImageData(string $size)

Loads image data if this post is an attachment



* Visibility: **public**


#### Arguments
* $size **string** - &lt;p&gt;thumbnail|medium|large|full&lt;/p&gt;



### getThumbnailId

    integer Chayka\WP\Models\PostModel::getThumbnailId()

Get post thumbnail id (thumbnail is an attachment post associated with this post)



* Visibility: **public**




### getThumbnailImage

    \Chayka\WP\Models\string(html) Chayka\WP\Models\PostModel::getThumbnailImage(string $size, \Chayka\WP\Models\array[key]=value $attrs)

Get thumbnail image HTML code (<img src=".

.."/>)
of the specified size and with HTML attributes

* Visibility: **public**


#### Arguments
* $size **string** - &lt;p&gt;thumbnail|post-thumbnail|medium|large|full|&lt;custom&gt;&lt;/p&gt;
* $attrs **Chayka\WP\Models\array[key]=value**



### getThumbnailImage_Medium

    \Chayka\WP\Models\string(html) Chayka\WP\Models\PostModel::getThumbnailImage_Medium(\Chayka\WP\Models\array[key]=value $attrs)

Get thumbnail image HTML code (<img src=".

.."/>)
of the specified size and with HTML attributes

* Visibility: **public**


#### Arguments
* $attrs **Chayka\WP\Models\array[key]=value**



### getThumbnailImage_Large

    \Chayka\WP\Models\string(html) Chayka\WP\Models\PostModel::getThumbnailImage_Large(\Chayka\WP\Models\array[key]=value $attrs)

Get thumbnail image HTML code (<img src=".

.."/>)
of the specified size and with HTML attributes

* Visibility: **public**


#### Arguments
* $attrs **Chayka\WP\Models\array[key]=value**



### getThumbnailImage_Full

    \Chayka\WP\Models\string(html) Chayka\WP\Models\PostModel::getThumbnailImage_Full(\Chayka\WP\Models\array[key]=value $attrs)

Get thumbnail image HTML code (<img src=".

.."/>)
of the specified size and with HTML attributes

* Visibility: **public**


#### Arguments
* $attrs **Chayka\WP\Models\array[key]=value**



### getThumbnailData

    \Chayka\WP\Models\array[key]=value Chayka\WP\Models\PostModel::getThumbnailData(string $size)

Get thumbnail image data (url, width, height, resized)
of the specified size



* Visibility: **public**


#### Arguments
* $size **string** - &lt;p&gt;thumbnail|post-thumbnail|medium|large|full|&lt;custom&gt;&lt;/p&gt;



### getThumbnailData_Thumbnail

    \Chayka\WP\Models\array[key]=value Chayka\WP\Models\PostModel::getThumbnailData_Thumbnail()

Get thumbnail image data (url, width, height, resized)
of the specified size



* Visibility: **public**




### getThumbnailData_Medium

    \Chayka\WP\Models\array[key]=value Chayka\WP\Models\PostModel::getThumbnailData_Medium()

Get thumbnail image data (url, width, height, resized)
of the specified size



* Visibility: **public**




### getThumbnailData_Large

    \Chayka\WP\Models\array[key]=value Chayka\WP\Models\PostModel::getThumbnailData_Large()

Get thumbnail image data (url, width, height, resized)
of the specified size



* Visibility: **public**




### getThumbnailData_Full

    \Chayka\WP\Models\array[key]=value Chayka\WP\Models\PostModel::getThumbnailData_Full()

Get thumbnail image data (url, width, height, resized)
of the specified size



* Visibility: **public**




### populateWpGlobals

    null|\WP_Post Chayka\WP\Models\PostModel::populateWpGlobals()

Populates this post for old school WP use.

Defines global variables $post, $authordata, $wp_the_query, etc.

* Visibility: **public**




### setJsonMetaFields

    mixed Chayka\WP\Models\PostModel::setJsonMetaFields(\Chayka\WP\Models\array(string) $metaFields)

Set meta fields that should be populated to json



* Visibility: **public**
* This method is **static**.


#### Arguments
* $metaFields **Chayka\WP\Models\array(string)**



### addJsonMetaField

    mixed Chayka\WP\Models\PostModel::addJsonMetaField(string $fieldName)

Add meta field name that should be populated to json



* Visibility: **public**
* This method is **static**.


#### Arguments
* $fieldName **string**



### removeJsonMetaField

    mixed Chayka\WP\Models\PostModel::removeJsonMetaField(string $fieldName)

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



### flushCache

    mixed Chayka\WP\Models\PostModel::flushCache()

Flushes cache used for selectById() and selectBySlug



* Visibility: **public**
* This method is **static**.




### getPostsCacheById

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::getPostsCacheById(integer $id)

Get post by $id from cache.

It gets to cache once it was unpacked by unpackDbRecord()

* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **integer**



### getPostsCacheBySlug

    \Chayka\WP\Models\PostModel Chayka\WP\Models\PostModel::getPostsCacheBySlug(string $slug)

Get post by $slug from cache.

It gets to cache once it was unpacked by unpackDbRecord()

* Visibility: **public**
* This method is **static**.


#### Arguments
* $slug **string**



### userCan

    mixed Chayka\WP\Helpers\AclReady::userCan(string $privilege, \Chayka\WP\Models\UserModel|null $user)





* Visibility: **public**
* This method is defined by [Chayka\WP\Helpers\AclReady](Chayka-WP-Helpers-AclReady.md)


#### Arguments
* $privilege **string**
* $user **[Chayka\WP\Models\UserModel](Chayka-WP-Models-UserModel.md)|null**


