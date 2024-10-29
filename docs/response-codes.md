# Response codes

Every API request to Optis server returns a standard HTTP status code in the response message.

## HTTP Status Codes

HTTP status code indicates the result of an API call.

For every successful or unsuccessful API call, one of the following HTTP Status Code is returned in the response message:

| HTTP Status Code   | Description |
| -------- | ------- |
| 200 OK | Successful request    |
| 401 Unauthorized | Authorization failed due to missing or invalid credentials     |
| 403 Forbidden   | Insufficient access for requested operation   |
| 452 System Exception   | Internal processes not related to client interaction with application are the cause of the failure  |
| 453 Validation Exception   | The request failed validation, modify the request and resubmit   |
| 455 ODS Error Exception   | ODS returned a message with transaction status ERROR   |
| 457 Permanent Error  | Permanent/Fatal error. Ex: Transaction Unavailable OR Record Not Found   |
| 458 Temporary Error   | Temporary Error. Ex: FDR processing error   |
