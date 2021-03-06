Chayka\WP\Plugin
===============






* Class name: Plugin
* Namespace: Chayka\WP
* This is an **abstract** class





Properties
----------


### $adminBar

    protected mixed $adminBar





* Visibility: **protected**
* This property is **static**.


### $needStyles

    protected mixed $needStyles = true





* Visibility: **protected**


### $currentDbVersion

    protected mixed $currentDbVersion = '1.0'





* Visibility: **protected**


### $consolePageUris

    protected mixed $consolePageUris = array()





* Visibility: **protected**


### $metaBoxUris

    protected mixed $metaBoxUris = array()





* Visibility: **protected**


### $shortcodeUris

    protected mixed $shortcodeUris = array()





* Visibility: **protected**


### $baseUrl

    protected mixed $baseUrl





* Visibility: **protected**


### $basePath

    protected mixed $basePath





* Visibility: **protected**


### $resSrcDir

    protected mixed $resSrcDir = ""





* Visibility: **protected**


### $resDistDir

    protected mixed $resDistDir = ""





* Visibility: **protected**


### $mediaMinimized

    protected mixed $mediaMinimized = false





* Visibility: **protected**


### $appId

    protected mixed $appId





* Visibility: **protected**


### $application

    protected mixed $application





* Visibility: **protected**


### $bower

    protected mixed $bower = null





* Visibility: **protected**


### $composer

    protected mixed $composer = null





* Visibility: **protected**


### $uriProcessing

    protected mixed $uriProcessing = false





* Visibility: **protected**
* This property is **static**.


### $instance

    protected mixed $instance = null





* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed Chayka\WP\Plugin::__construct(string $__file__, array $routes)

Plugin Constructor.



* Visibility: **public**


#### Arguments
* $__file__ **string** - &lt;p&gt;pass __FILE__&lt;/p&gt;
* $routes **array**



### getInstance

    static Chayka\WP\Plugin::getInstance()

Get singleton instance



* Visibility: **public**
* This method is **static**.




### dirPath

    string Chayka\WP\Plugin::dirPath(string $__file__)

Returns file's dir path



* Visibility: **protected**
* This method is **static**.


#### Arguments
* $__file__ **string** - &lt;p&gt;use __FILE__&lt;/p&gt;



### dirUrl

    string Chayka\WP\Plugin::dirUrl(string $__file__)

Returns file's dir url



* Visibility: **protected**
* This method is **static**.


#### Arguments
* $__file__ **string** - &lt;p&gt;use __FILE__&lt;/p&gt;



### getView

    \Chayka\MVC\View Chayka\WP\Plugin::getView()

Get view with set up basepathh



* Visibility: **public**
* This method is **static**.




### getAppId

    string Chayka\WP\Plugin::getAppId()

Get App Id



* Visibility: **public**




### getClassName

    string Chayka\WP\Plugin::getClassName()

Get class name



* Visibility: **public**




### getNamespace

    string Chayka\WP\Plugin::getNamespace()

Get namespace



* Visibility: **public**




### getCallbackMethod

    callable Chayka\WP\Plugin::getCallbackMethod(string $method)

Get callback method defined in this class



* Visibility: **public**


#### Arguments
* $method **string**



### getBasePath

    string Chayka\WP\Plugin::getBasePath()

Get base path



* Visibility: **public**




### getPath

    String Chayka\WP\Plugin::getPath(String $path)

Get abs path for relative path



* Visibility: **public**


#### Arguments
* $path **String**



### getPathRes

    String Chayka\WP\Plugin::getPathRes($relativeResPath)

Get abs res for path relative to '/res'



* Visibility: **public**


#### Arguments
* $relativeResPath **mixed**



### getBaseUrl

    string Chayka\WP\Plugin::getBaseUrl()

Get base url



* Visibility: **public**




### baseUrl

    mixed Chayka\WP\Plugin::baseUrl()

Output base url.

Can use in templates

* Visibility: **public**
* This method is **static**.




### getUrl

    String Chayka\WP\Plugin::getUrl(String $path)

Get abs url for relative path



* Visibility: **public**


#### Arguments
* $path **String**



### getUrlRes

    String Chayka\WP\Plugin::getUrlRes($relativeResPath)

Get abs url for path relative to '/res'



* Visibility: **public**


#### Arguments
* $relativeResPath **mixed**



### dbUpdate

    mixed Chayka\WP\Plugin::dbUpdate(\Chayka\WP\array(String) $versionHistory)

Perform update based on db structure version history

DB Version history

* Visibility: **public**


#### Arguments
* $versionHistory **Chayka\WP\array(String)**



### init

    \Chayka\WP\Plugin Chayka\WP\Plugin::init()

This function instantiates Plugin's singleton and returns it



* Visibility: **public**
* This method is **static**.




### addSupport_UriProcessing

    mixed Chayka\WP\Plugin::addSupport_UriProcessing()

Enables plugin ability to process request uris, based on the registered routes



* Visibility: **public**




### registerRoutes

    mixed Chayka\WP\Plugin::registerRoutes()

Routes are to be added here via $this->addRoute();



* Visibility: **public**




### addRoute

    mixed Chayka\WP\Plugin::addRoute(string $label, string $urlPattern, array $defaults, array $paramPatterns)





* Visibility: **public**


#### Arguments
* $label **string**
* $urlPattern **string**
* $defaults **array**
* $paramPatterns **array**



### addRestRoute

    mixed Chayka\WP\Plugin::addRestRoute(string $modelSlug, string $restUrlPattern, array $restParamPatterns, string $modelClassName, string $controller, array $defaults)

Add set of route to rest controller



* Visibility: **public**


#### Arguments
* $modelSlug **string** - &lt;p&gt;e.g. &#039;post-model&#039;&lt;/p&gt;
* $restUrlPattern **string** - &lt;p&gt;e.g &#039;/?id&#039;&lt;/p&gt;
* $restParamPatterns **array** - &lt;p&gt;e.g. [&#039;id&#039;=&gt;&#039;/^\d+$/&#039;]&lt;/p&gt;
* $modelClassName **string** - &lt;p&gt;e.g. &#039;\Chayka\WP\Models\PostModel&#039;&lt;/p&gt;
* $controller **string** - &lt;p&gt;e.g. &#039;post-model&#039;&lt;/p&gt;
* $defaults **array**



### addRestRoutes

    mixed Chayka\WP\Plugin::addRestRoutes(string $modelSlug, string $modelsSlug, string $restUrlPattern, array $restParamPatterns, string $modelClassName, string $controller, string $listAction, array $defaults)

Add set of routes to rest controller



* Visibility: **public**


#### Arguments
* $modelSlug **string** - &lt;p&gt;e.g. &#039;post-model&#039;&lt;/p&gt;
* $modelsSlug **string** - &lt;p&gt;e.g. &#039;post-models&#039;&lt;/p&gt;
* $restUrlPattern **string** - &lt;p&gt;e.g &#039;/?id&#039;&lt;/p&gt;
* $restParamPatterns **array** - &lt;p&gt;e.g. [&#039;id&#039;=&gt;&#039;/^\d+$/&#039;]&lt;/p&gt;
* $modelClassName **string** - &lt;p&gt;e.g. &#039;\Chayka\WP\Models\PostModel&#039;&lt;/p&gt;
* $controller **string** - &lt;p&gt;e.g. &#039;post-model&#039;&lt;/p&gt;
* $listAction **string**
* $defaults **array**



### processRequest

    string Chayka\WP\Plugin::processRequest($requestUri)

Processes request uri and returns response



* Visibility: **public**


#### Arguments
* $requestUri **mixed**



### renderRequest

    mixed Chayka\WP\Plugin::renderRequest($requestUri)

Processes request uri and outputs response



* Visibility: **public**


#### Arguments
* $requestUri **mixed**



### registerCustomPostTypes

    mixed Chayka\WP\Plugin::registerCustomPostTypes()

Custom post type are to be added here



* Visibility: **public**




### registerTaxonomies

    mixed Chayka\WP\Plugin::registerTaxonomies()

Custom Taxonomies are to be added here



* Visibility: **public**




### registerSidebars

    mixed Chayka\WP\Plugin::registerSidebars()

Custom Sidebars are to be added here via $this->registerSidbar();



* Visibility: **public**




### registerSidebar

    mixed Chayka\WP\Plugin::registerSidebar(string $name, string $id)

Register custom sidbar



* Visibility: **public**


#### Arguments
* $name **string**
* $id **string**



### addSupport_PostProcessing

    mixed Chayka\WP\Plugin::addSupport_PostProcessing(integer $priority)

Enables post modofication processing.

You need to implement savePost(), deletePost() [and trashedPost()].

* Visibility: **public**


#### Arguments
* $priority **integer**



### savePost

    mixed Chayka\WP\Plugin::savePost(integer $postId, \WP_Post $post)

This is a hook for save_post



* Visibility: **public**


#### Arguments
* $postId **integer**
* $post **WP_Post**



### deletePost

    mixed Chayka\WP\Plugin::deletePost(integer $postId)

This is a hook for delete_post



* Visibility: **public**


#### Arguments
* $postId **integer**



### trashedPost

    mixed Chayka\WP\Plugin::trashedPost(integer $postId)

This is a hook for trashed_post



* Visibility: **public**


#### Arguments
* $postId **integer**



### addSupport_CustomPermalinks

    mixed Chayka\WP\Plugin::addSupport_CustomPermalinks()

Enables custom link formats.

You need to implement postPermalink(), termLink(), userLink() and commentPermalink() methods.

* Visibility: **public**




### postPermalink

    string Chayka\WP\Plugin::postPermalink(string $permalink, \WP_Post $post, boolean $leavename)

This is a hook for post_link and post_type_link



* Visibility: **public**


#### Arguments
* $permalink **string**
* $post **WP_Post**
* $leavename **boolean**



### termLink

    string Chayka\WP\Plugin::termLink(string $link, object $term, string $taxonomy)

This is a hook for term_link



* Visibility: **public**


#### Arguments
* $link **string**
* $term **object**
* $taxonomy **string**



### userLink

    string Chayka\WP\Plugin::userLink(string $link, integer $userId, string $nicename)

This is a hook for author_link



* Visibility: **public**


#### Arguments
* $link **string**
* $userId **integer**
* $nicename **string**



### commentPermalink

    string Chayka\WP\Plugin::commentPermalink(string $permalink, object $comment)

This is a hook for get_comment_link



* Visibility: **public**


#### Arguments
* $permalink **string**
* $comment **object**



### isMediaMinimized

    boolean Chayka\WP\Plugin::isMediaMinimized()

Check if media minimization is enabled



* Visibility: **public**




### setMediaMinimized

    mixed Chayka\WP\Plugin::setMediaMinimized(boolean $mediaMinimized)

Enable or disable media minimization



* Visibility: **public**


#### Arguments
* $mediaMinimized **boolean**



### getResSrcDir

    string Chayka\WP\Plugin::getResSrcDir()

Get /res relative 'src' dir



* Visibility: **public**




### setResSrcDir

    mixed Chayka\WP\Plugin::setResSrcDir(string $resSrcDir)

Set /res relative 'src' dir



* Visibility: **public**


#### Arguments
* $resSrcDir **string**



### getResDistDir

    mixed Chayka\WP\Plugin::getResDistDir()

Get /res relative 'dist' dir



* Visibility: **public**




### setResDistDir

    mixed Chayka\WP\Plugin::setResDistDir(mixed $resDistDir)

Set /res relative 'dist' dir



* Visibility: **public**


#### Arguments
* $resDistDir **mixed**



### registerResources

    mixed Chayka\WP\Plugin::registerResources(boolean $minimize)

Register scripts and styles here using $this->registerScript() and $this->registerStyle()



* Visibility: **public**


#### Arguments
* $minimize **boolean**



### setScriptLocation

    mixed Chayka\WP\Plugin::setScriptLocation($handle, boolean $inFooter)

Set script rendering location (head|footer)



* Visibility: **public**


#### Arguments
* $handle **mixed**
* $inFooter **boolean**



### enqueueStyle

    mixed Chayka\WP\Plugin::enqueueStyle(string $handle, string|boolean $relativeResPath, array $dependencies, boolean $version, string $media)

Alias to wp_enqueue_style, but the path is relative to '/res'



* Visibility: **public**


#### Arguments
* $handle **string**
* $relativeResPath **string|boolean**
* $dependencies **array**
* $version **boolean**
* $media **string**



### registerStyle

    mixed Chayka\WP\Plugin::registerStyle(string $handle, string $relativeResPath, array $dependencies, boolean $version, string $media)

Alias to wp_register_style, but the path is relative to '/res'



* Visibility: **public**


#### Arguments
* $handle **string**
* $relativeResPath **string**
* $dependencies **array**
* $version **boolean**
* $media **string**



### registerMinimizedStyle

    mixed Chayka\WP\Plugin::registerMinimizedStyle(string $minHandle, string $relativeResDistPath, array $handles, boolean $version, string $media)

Register minimized style file that contains all the min-cat styles defined by $handles.



* Visibility: **public**


#### Arguments
* $minHandle **string**
* $relativeResDistPath **string**
* $handles **array**
* $version **boolean**
* $media **string**



### unregisterStyle

    mixed Chayka\WP\Plugin::unregisterStyle($handle)

Alias to wp_deregister_style



* Visibility: **public**


#### Arguments
* $handle **mixed**



### enqueueScript

    mixed Chayka\WP\Plugin::enqueueScript(string $handle, string|boolean $relativeResPath, array $dependencies, boolean $version, boolean $inFooter)

Alias to wp_register_script, but the path is relative to '/res'



* Visibility: **public**


#### Arguments
* $handle **string**
* $relativeResPath **string|boolean**
* $dependencies **array**
* $version **boolean**
* $inFooter **boolean**



### registerScript

    mixed Chayka\WP\Plugin::registerScript(string $handle, string $relativeResPath, array $dependencies, boolean $version, boolean $inFooter)

Alias to wp_register_script, but the path is relative to '/res'



* Visibility: **public**


#### Arguments
* $handle **string**
* $relativeResPath **string**
* $dependencies **array**
* $version **boolean**
* $inFooter **boolean**



### registerNgScript

    mixed Chayka\WP\Plugin::registerNgScript($handle, $relativeResPath, array $dependencies, callable|null $enqueueCallback, boolean $version, boolean $inFooter)





* Visibility: **public**


#### Arguments
* $handle **mixed**
* $relativeResPath **mixed**
* $dependencies **array**
* $enqueueCallback **callable|null**
* $version **boolean**
* $inFooter **boolean**



### registerMinimizedScript

    mixed Chayka\WP\Plugin::registerMinimizedScript(string $minHandle, string $relativeResDistPath, array $handles, boolean $version, boolean $inFooter)

Register minimized script file that contains all the min-cat scripts defined by $handles.



* Visibility: **public**


#### Arguments
* $minHandle **string**
* $relativeResDistPath **string**
* $handles **array**
* $version **boolean**
* $inFooter **boolean**



### unregisterScript

    mixed Chayka\WP\Plugin::unregisterScript(string $handle)

Alias to wp_deregister_script



* Visibility: **public**


#### Arguments
* $handle **string**



### registerScriptNls

    mixed Chayka\WP\Plugin::registerScriptNls($handle, $relativeResPath, array $dependencies)

Not implemented yet and to be revised



* Visibility: **public**


#### Arguments
* $handle **mixed**
* $relativeResPath **mixed**
* $dependencies **array**



### enqueueScriptStyle

    mixed Chayka\WP\Plugin::enqueueScriptStyle(string $handle, boolean $scriptInFooter)





* Visibility: **public**


#### Arguments
* $handle **string**
* $scriptInFooter **boolean**



### getBower

    array|boolean Chayka\WP\Plugin::getBower(boolean $minimize)

Read and parse bower config



* Visibility: **public**


#### Arguments
* $minimize **boolean**



### registerBowerResources

    mixed Chayka\WP\Plugin::registerBowerResources(boolean $overrideWithNew)

This function discovers installed bower packages and registers them if they are not already registered
if true passed, newer versions will override older ones



* Visibility: **public**


#### Arguments
* $overrideWithNew **boolean**



### registerBowerComponent

    mixed Chayka\WP\Plugin::registerBowerComponent(string $name, string $path, boolean $overrideWithNew)

Registers bower component
$path is relative to baseDir



* Visibility: **public**


#### Arguments
* $name **string**
* $path **string**
* $overrideWithNew **boolean**



### getComposer

    array|boolean Chayka\WP\Plugin::getComposer()

Read and parse composer config



* Visibility: **public**




### registerComposerPlugins

    mixed Chayka\WP\Plugin::registerComposerPlugins()

Go through vendor folder if it exists.

Find composer.json
Call "wp-init" callback.

'$ composer install' should be called before

* Visibility: **public**




### registerComposerPlugin

    mixed Chayka\WP\Plugin::registerComposerPlugin(string $name, string $path)

Register composer Chayka plugin



* Visibility: **public**


#### Arguments
* $name **string**
* $path **string**



### registerActions

    mixed Chayka\WP\Plugin::registerActions()

Register your action hooks here using $this->addAction();



* Visibility: **public**




### addAction

    boolean|void Chayka\WP\Plugin::addAction($action, string|array $method, integer $priority, integer $numberOfArguments)

Alias to add_action, but if the $method is a string then
$this->getCallbackMethod($method) is used instead.



* Visibility: **public**


#### Arguments
* $action **mixed**
* $method **string|array**
* $priority **integer**
* $numberOfArguments **integer**



### removeAction

    boolean Chayka\WP\Plugin::removeAction($tag, $callback, integer $priority)

Alias to remove_action, but if the $method is a string and method exists then
$this->getCallbackMethod($callback) is used instead.



* Visibility: **public**


#### Arguments
* $tag **mixed**
* $callback **mixed**
* $priority **integer**



### registerFilters

    mixed Chayka\WP\Plugin::registerFilters()

Register your action hooks here using $this->addFilter();



* Visibility: **public**




### addFilter

    boolean|void Chayka\WP\Plugin::addFilter($filter, $method, integer $priority, integer $numberOfArguments)

Alias to add_filter, but if the $method is a string then
$this->getCallbackMethod($method) is used instead.



* Visibility: **public**


#### Arguments
* $filter **mixed**
* $method **mixed**
* $priority **integer**
* $numberOfArguments **integer**



### removeFilter

    boolean Chayka\WP\Plugin::removeFilter($tag, $callback, integer $priority)

Alias to remove_filter, but if the $method is a string and method exists then
$this->getCallbackMethod($callback) is used instead.



* Visibility: **public**


#### Arguments
* $tag **mixed**
* $callback **mixed**
* $priority **integer**



### addSupport_ConsolePages

    mixed Chayka\WP\Plugin::addSupport_ConsolePages()

Enables support for console pages that will be typically rendered by AdminController.

You should implement registerConsolePages();

* Visibility: **public**




### registerConsolePages

    mixed Chayka\WP\Plugin::registerConsolePages()

Override to add addConsolePage() calls



* Visibility: **public**




### renderConsolePage

    mixed Chayka\WP\Plugin::renderConsolePage()

Callback method that will render console pages using AdminController



* Visibility: **public**




### addConsolePage

    mixed Chayka\WP\Plugin::addConsolePage(string $title, string $capability, string $menuSlug, string $renderUri, string $relativeResIconUrl, integer $position)

Add Console Page. Much like add_menu_page,
but instead of callback you provide some controller uri (e.g. 'admin/some-action')
see https://developer.wordpress.org/resource/dashicons/#wordpress for icons



* Visibility: **public**


#### Arguments
* $title **string**
* $capability **string**
* $menuSlug **string**
* $renderUri **string**
* $relativeResIconUrl **string**
* $position **integer**



### addConsoleSubPage

    mixed Chayka\WP\Plugin::addConsoleSubPage($parentSlug, $title, $capability, $menuSlug, string $renderUri)

Add Console Page. Much like add_submenu_page,
but instead of callback you provide some controller uri (e.g. 'admin/some-action')



* Visibility: **public**


#### Arguments
* $parentSlug **mixed**
* $title **mixed**
* $capability **mixed**
* $menuSlug **mixed**
* $renderUri **string**



### addSupport_Metaboxes

    mixed Chayka\WP\Plugin::addSupport_Metaboxes()

Enable metaboxes rendering using MetaboxController.

You should implement registerMetaBoxes().

* Visibility: **public**




### registerMetaBoxes

    mixed Chayka\WP\Plugin::registerMetaBoxes()

Override to add addMetaBox() calls;



* Visibility: **public**




### renderMetaBox

    mixed Chayka\WP\Plugin::renderMetaBox(\WP_Post $post, string $box)

Callback for rendering metaboxes.



* Visibility: **public**


#### Arguments
* $post **WP_Post**
* $box **string**



### updateMetaBoxes

    mixed Chayka\WP\Plugin::updateMetaBoxes(integer $postId, \WP_Post $post)

Callback for 'save_post' hook, updating metabox, should be revised (implement logic here).



* Visibility: **public**


#### Arguments
* $postId **integer**
* $post **WP_Post**



### addMetaBox

    mixed Chayka\WP\Plugin::addMetaBox(string $id, string $title, string $renderUri, string $context, string $priority, string|array $screen)

Add Metabox



* Visibility: **public**


#### Arguments
* $id **string**
* $title **string**
* $renderUri **string**
* $context **string** - &lt;p&gt;&#039;normal&#039;, &#039;advanced&#039;, or &#039;side&#039;&lt;/p&gt;
* $priority **string** - &lt;p&gt;&#039;high&#039;, &#039;core&#039;, &#039;default&#039; or &#039;low&#039;&lt;/p&gt;
* $screen **string|array** - &lt;p&gt;post type&lt;/p&gt;



### addMetaBoxes

    mixed Chayka\WP\Plugin::addMetaBoxes()

Callback method for 'add_meta_boxes' hook,
adding metaboxes when rendering post editor page



* Visibility: **public**




### removeMetaBox

    mixed Chayka\WP\Plugin::removeMetaBox(string $id, string|array $pages, string $context)

Remove registered metabox.

Handy for blocking metaboxes from parent themes.

more info http://codex.wordpress.org/Function_Reference/remove_meta_box

* Visibility: **public**


#### Arguments
* $id **string**
* $pages **string|array**
* $context **string** - &lt;p&gt;&#039;normal&#039;, &#039;advanced&#039;, or &#039;side&#039;.&lt;/p&gt;



### unregisterMetaBoxes

    mixed Chayka\WP\Plugin::unregisterMetaBoxes()

Callback method for 'add_meta_boxes' hook,
adding metaboxes when rendering post editor page



* Visibility: **public**




### registerShortcodes

    mixed Chayka\WP\Plugin::registerShortcodes()

Override to add addShortcodes() calls;



* Visibility: **public**




### addShortcode

    mixed Chayka\WP\Plugin::addShortcode(string $shortcode, string $uri)

Alias to add_shortcode(), but instead of callback ShortcodeController renderer is used



* Visibility: **public**


#### Arguments
* $shortcode **string**
* $uri **string**



### renderShortcode

    string Chayka\WP\Plugin::renderShortcode($atts, $content, $shortcode)

Callback for shortcode rendering



* Visibility: **public**


#### Arguments
* $atts **mixed**
* $content **mixed**
* $shortcode **mixed**



### showAdminBar

    mixed Chayka\WP\Plugin::showAdminBar($show)





* Visibility: **public**


#### Arguments
* $show **mixed**



### hideAdminBar

    mixed Chayka\WP\Plugin::hideAdminBar()

deprecated *



* Visibility: **public**




### showAdminBarToAdminOnly

    mixed Chayka\WP\Plugin::showAdminBarToAdminOnly()

deprecated *



* Visibility: **public**




### isAdminBarShown

    mixed Chayka\WP\Plugin::isAdminBarShown($show)

deprecated *



* Visibility: **public**


#### Arguments
* $show **mixed**


