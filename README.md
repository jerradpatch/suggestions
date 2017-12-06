# suggestions
suggestions


```javascript
removeFromSimpleArray(myArray, val) {
    for (var i = myArray.length - 1; i >= 0; i--) {
        if(myArray[i] === (val["id"] || val["code"] || val["geoId"] || val["name"] || val))
            myArray.splice(i, 1);
    }
}
```
