Chayka\WP\Helpers\JsonHelper
===============






* Class name: JsonHelper
* Namespace: Chayka\WP\Helpers
* Parent class: [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)







Methods
-------


### respondErrors

    mixed Chayka\Helpers\JsonHelper::respondErrors($errors, null $payload, integer $httpResponseCode)

Wrap multiple errors into {'payload': .

.., 'code': ..., 'message': ...} envelope.
Set http response code to $httpResponseCode = 400.
And then die() it.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)


#### Arguments
* $errors **mixed**
* $payload **null**
* $httpResponseCode **integer**



### packWpErrors

    array Chayka\WP\Helpers\JsonHelper::packWpErrors(\WP_Error $errors)

Wrap WP_Errors object into assoc array.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $errors **WP_Error**



### encode

    string Chayka\Helpers\JsonHelper::encode($value)

Encode recursively provided $value.

If $value or it's properties are JsonReady, packToJson() will be used.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)


#### Arguments
* $value **mixed**



### packObject

    array|string Chayka\Helpers\JsonHelper::packObject(mixed $obj)

Create assoc array from provided object.

If $obj or it's properties are JsonReady, packToJson() will be used.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)


#### Arguments
* $obj **mixed**



### packResponse

    string Chayka\Helpers\JsonHelper::packResponse(string $payload, integer $code, string $message)

Wrap json response into {'payload': .

.., 'code': ..., 'message': ...} envelope

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)


#### Arguments
* $payload **string**
* $code **integer**
* $message **string**



### respond

    mixed Chayka\Helpers\JsonHelper::respond(string $payload, integer $code, string $message)

Wrap json response into {'payload': .

.., 'code': ..., 'message': ...} envelope.
And then die() it.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)


#### Arguments
* $payload **string**
* $code **integer**
* $message **string**



### respondException

    mixed Chayka\Helpers\JsonHelper::respondException(\Exception $e, string $code)

Wrap Exception into {'payload': .

.., 'code': ..., 'message': ...} envelope.
Set http response code to 500.
And then die() it.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)


#### Arguments
* $e **Exception**
* $code **string**



### respondError

    mixed Chayka\Helpers\JsonHelper::respondError(string $message, integer $code, null $payload, integer $httpResponseCode)

Wrap error into {'payload': .

.., 'code': ..., 'message': ...} envelope.
Set http response code to $httpResponseCode = 400.
And then die() it.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Chayka\Helpers\JsonHelper](Chayka-Helpers-JsonHelper.md)


#### Arguments
* $message **string**
* $code **integer**
* $payload **null**
* $httpResponseCode **integer**


