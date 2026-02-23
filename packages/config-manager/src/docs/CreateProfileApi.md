# CreateProfileApi

All URIs are relative to *https://raw.githubusercontent.com/api/config-manager/v2*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**createProfile**](#createprofile) | **POST** /profiles | Create a new profile|

# **createProfile**
> Profile createProfile(createProfileRequest)

Create and optionally activate a new profile.

### Example

```typescript
import {
    CreateProfileApi,
    Configuration,
    CreateProfileRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new CreateProfileApi(configuration);

let createProfileRequest: CreateProfileRequest; //

const { status, data } = await apiInstance.createProfile(
    createProfileRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createProfileRequest** | **CreateProfileRequest**|  | |


### Return type

**Profile**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json, text/plain


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | Created |  -  |
|**304** | Not Modified |  -  |
|**400** | Bad Request |  -  |
|**500** | Internal Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

