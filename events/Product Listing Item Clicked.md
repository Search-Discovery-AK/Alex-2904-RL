# Product Listing Item Clicked

## Javascript Code
```js
window.appEventData2904RL = window.appEventData2904RL || [];
appEventData2904RL.push({
  "event": "Product Listing Item Clicked",
    "listingDisplayed": {
        "listingDriver": "<listingDriver>",
        "sortOrder": "<sortOrder>"
    },
    "listingItemClicked": {
        "filterList": "<filterList>",
        "listing": [
            {
                "productInfo": {
                    "brand": "<brand>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|filterList|string|A twice delimited string of filterType and filterValue pairs.  Use ~ between type and value.  Use | between pairs|sort~price ascending|color~green|size~medium|||||||
|listingDriver|string|Describes the action that caused the listing to be displayed|Onsite Search, Curated Assortment, Navigation|||||||
|sortOrder|string|Indicates the sort order.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
