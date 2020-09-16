
# How To Install

```sh
npm install bar-chart-console
```

# How To Use

```js
const barChart = require('bar-chart-console')

let data = {
  "label"  : ["2000","2001","2002","2020"],
  "value" : [1,5,3,2],
};

barChart.draw(data);
```
# Output
```sh
    5        ||||             
    4        ||||             
    3        ||||  ||||       
    2        ||||  ||||  |||| 
    1  ||||  ||||  ||||  |||| 
      2000   2001   2002  2020  

```
