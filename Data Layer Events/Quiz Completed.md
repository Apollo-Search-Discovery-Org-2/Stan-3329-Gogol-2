# Quiz Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "survey_complete",
  "apollo_event": "Quiz Completed",
    "ecommerce": {
        "items": [
            {
                "item_finding_method": "<item_finding_method>"
            }
        ]
    },
    "event_data": {
        "name": "<name>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.items[n].item_finding_method|string|Captures the ID associated with exit links used.||||||||
|event_data.name|string|Captures the human-friendly quiz name.|Floor Chooser, Swim Finder, Movie Decider, My Next Book|||||||




