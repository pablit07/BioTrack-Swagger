# Swagger\Client\DefaultApi

All URIs are relative to *https://mcmonitoring.agr.illinois.gov/serverjson.asp*

Method | HTTP request | Description
------------- | ------------- | -------------
[**allActions**](DefaultApi.md#allactions) | **POST** / | All actions

# **allActions**
> allActions($body)

All actions

This is the only endpoint provided. The type of action is differentiated by the action property in the POST body.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \Swagger\Client\Model\null(); //  | 

try {
    $apiInstance->allActions($body);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->allActions: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [****](../Model/.md)|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

