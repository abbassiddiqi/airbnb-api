# Airbnb API (demo)
Get the flats data in json format using the following fetch utility.

```javascript
fetch("https://cdn.jsdelivr.net/gh/abbassiddiqi/airbnb-api@bbd1300a/flats.json")
  .then(response => response.json())
  .then(data => {
    console.log(data);
  })
```