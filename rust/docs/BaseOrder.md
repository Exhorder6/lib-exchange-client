# BaseOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cl_ord_id** | **String** | Reference field provided by client. Cannot exceed 20 characters, only alphanumeric characters are allowed. | 
**ord_type** | [**crate::models::OrdType**](ordType.md) |  | 
**symbol** | **String** | Blockchain symbol identifier | 
**side** | [**crate::models::Side**](side.md) |  | 
**order_qty** | **f64** | The order size in the terms of the base currency | 
**time_in_force** | Option<[**crate::models::TimeInForce**](TimeInForce.md)> |  | [optional]
**price** | Option<**f64**> | The limit price for the order | [optional]
**expire_date** | Option<**i32**> | expiry date in the format YYYYMMDD | [optional]
**min_qty** | Option<**f64**> | The minimum quantity required for an IOC fill | [optional]
**stop_px** | Option<**f64**> | The limit price for the order | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


