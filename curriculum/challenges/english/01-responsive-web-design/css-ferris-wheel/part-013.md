---
id: 6140d3dc359b371b1a21d783
title: Part 13
challengeType: 0
dashedName: part-13
---

# --description--

Time to position the cabins around the wheel. Select the first `.cabin` element. Set the `right` property to `-8.5%` and the `top` property to `50%`.

# --hints--

Test 1

```js

```

# --seed--

## --seed-contents--

```html
<!DOCTYPE html>
<html lang="en" >
  <head>
    <meta charset="UTF-8">
    <title> Learn CSS Animations by Building a Ferris Wheel</title>
    <link rel="stylesheet" href="./styles.css">
  </head>
  <body>
    <span class="line"></span>
    <span class="line"></span>
    <span class="line"></span>
    <span class="line"></span>
    <span class="line"></span>
    <span class="line"></span>

    <div class="cabin"></div>
    <div class="cabin"></div>
    <div class="cabin"></div>
    <div class="cabin"></div>
    <div class="cabin"></div>
    <div class="cabin"></div>
  </body>
</html>
```

```css
.wheel {
  border: 2px solid black;
  border-radius: 50%;
  margin-left: 50px;
  position: absolute;
  height: 500px;
  width: 500px;
}

.line {
  background-color: black;
  width: 50%;
  height: 2px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform-origin: 0% 0%;
}

.line:nth-of-type(2) {
  transform: rotate(60deg);
}
.line:nth-of-type(3) {
  transform: rotate(120deg);
}
.line:nth-of-type(4) {
  transform: rotate(180deg);
}
.line:nth-of-type(5) {
  transform: rotate(240deg);
}
.line:nth-of-type(6) {
  transform: rotate(300deg);
}

.cabin {
  background-color: red;
  width: 80px;
  height: 100px;
  position: absolute;
  border: 2px solid;
  transform-origin: 50% 0%;
}

--fcc-editable-region--

--fcc-editable-region--
```
