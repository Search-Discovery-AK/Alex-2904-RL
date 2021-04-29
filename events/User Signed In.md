# User Signed In

## Javascript Code
```js
window.appEventData2904RL = window.appEventData2904RL || [];
appEventData2904RL.push({
  "event": "User Signed In",
    "user": {
        "hasPersistedCart": "<hasPersistedCart>",
        "loyalty": {
            "memberId": "<memberId>",
            "memberStatus": "<memberStatus>"
        },
        "loyaltyPoints": "<loyaltyPoints>",
        "profileAttributesList": "<profileAttributesList>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|hasPersistedCart|boolean|Indicator of the user has a persisted shopping cart|TRUE, FALSE|||||||
|loyaltyPoints|integer|Number of loyalty points |100, 101, 1000||||0|||
|memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|profileAttributesList|string|A twice delimited string of key / value pairs.  Use ~ between key and value.  Use | between pairs|homeStore~234|loyaltyTier~gold|memberSince~2002|||||||
