# web-app-using-apis

## How to use weather api to get weather information

```javascript
const api = `https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${long}&units=metric&appid=ddfaba4398b491fa4ef3e29a5e934c6e`;

const response = await fetch(api);
const data = await response.json();

console.log(data)
```
