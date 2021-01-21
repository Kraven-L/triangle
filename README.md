```js

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      .polygon {
        width: 200px;
        height: 200px;
        background: rgb(255, 169, 10);
        border: 1px solid #333;
        position: relative;
      }
      .big {
        width: 0;
        height: 0;
        border-color: #00ccff transparent transparent #00ccff;
        border-width: 20px 20px 20px 20px;
        border-style: solid;
        position: relative;
      }
      .small {
        width: 30px;
        height: 30px;
        background:rgb(255, 169, 10);
        position: absolute;
        top: -15px;
        left: -15px;
      }
    </style>
  </head>
  <body>
    <div class="polygon">
      <div class="big">
        <div class="small"></div>
      </div>
    </div>
  </body>
</html>
```
