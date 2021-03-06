<html><ac:structured-macro ac:name="info" ac:schema-version="1"><ac:rich-text-body><p>Updated at <code>2022-06-16T11:40:37.367Z</code> by <code>sergiozc</code></p></ac:rich-text-body></ac:structured-macro><ac:structured-macro ac:name="note" ac:schema-version="1"><ac:rich-text-body><p>Do not edit this page manually as its content is updated automatically.</p></ac:rich-text-body></ac:structured-macro> </html>

## Error Codes


 
| Code | Name | Description | Action |
| ---- | ---- | ----------- | ------ |
| APPCONF-ERR-1101 | HTTP_ERROR_REQUEST | aRequest failed and http error has occurred. | Check the http error code for more information and other more specific error logs. |
| APPCONF-ERR-1101 | INVALID_JSON_REQUEST | The format of the JSON is not valid, so, the draft is discarded | Check the format of thenincoming draft, it must be a well-formatted JSON |
| APPCONF-ERR-1201 | CACHE_ERROR | A cache miss error occurred as the configuration requested by the device does not exist. | Check if requested data are correct and if this configuration exists or it is saved in database. |
| APPCONF-ERR-1202 | PUBLISHED_ENTRY_ERROR | This configuration cannot be published since it is not previously saved as a draft. Unknown published entry. | Create a draft of this configuration before publish it and check if an entry was created in the database. |
| APPCONF-ERR-2100 | UNSIGNED_CONFIG_ERROR | The service needs to generate a signature of the response sent to the users and this could not be completed because there is an error in the provided certificate. | Check if there are errors in the provided certificate and review logs. |
| APPCONF-ERR-2200 | SIGNATURE_ERROR | There is an error with the provided signature configuration since PrivateKey or certificate cannot be found in the keystore. | Check the signature configuration and the provided certificate or if the specified path is correct. |
| APPCONF-ERR-3000 | UNKNOWN_ERROR | An unexpected internal error has occurred. This may happen because there is a problem with the database connection or with redis. | Review logs, check the database connection and if redis is working. Contact with support for more information. |
