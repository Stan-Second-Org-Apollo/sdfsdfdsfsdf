# Content Listing Displayed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Content Listing Displayed",
    "listingDisplayed": {
        "displayCount": "<displayCount>",
        "listingDriver": "<listingDriver>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|displayCount|integer|The total number of items displayed out of all returned items. (Integer)|10, 20, 30, 40||||0|||
|listingDriver|string|Describes the action that caused the listing to be displayed|Onsite Search, Curated Assortment, Navigation|||||||
