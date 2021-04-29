# User Signed Out

## Javascript Code
```js
window.appEventData2904RL = window.appEventData2904RL || [];
appEventData2904RL.push({
  "event": "User Signed Out",
    "user": {
        "custKey": "<custKey>",
        "loginStatus": "<loginStatus>",
        "profileAttributesList": "<profileAttributesList>",
        "system": "<system>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|profileAttributesList|string|A twice delimited string of key / value pairs.  Use ~ between key and value.  Use | between pairs|homeStore~234|loyaltyTier~gold|memberSince~2002|||||||
|system|string|Describes the system that the user is logged into.  (rarely used). |admin, shop, member|||||||
