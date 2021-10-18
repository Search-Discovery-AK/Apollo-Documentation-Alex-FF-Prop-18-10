# Product Location Listing Item Clicked

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData1810 = window.appEventData1810 || [];
appEventData1810.push({
  "event": "Product Location Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "productInfo": {
                    "sku": "<sku>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|sku|string|Stock Keeping Unit \(SKU\) Unique Identifier of specific item \(typically\) held in inventory.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level below productID for products with SKU variants. |34567890, 4567890, 00155-large-cornflower|||||||




