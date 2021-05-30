# ArcherJS

Advanced HTML5 Canvas JavaScript library for circle and arc manipulation - and that's it.

- 📙 No external libraries, good ol' plain JS

- 💡 Super-lightweight (1kB)

- 🕐 Learn in 1 minute, save you hours

Good for drawing partial circles in relation to angles.

## Basic Usage

### Selecting the canvas

```javascript
const canvas = document.getElementById("canvas");
const selected = ArcherJS(canvas);
```

### Drawing a 70° circle with a radius of 50px

```javascript
const xCoordinate = 100;
const yCoordinate = 100;
selected.fromAngle(xCoordinate, yCoordinate, 50, 0, 70);
```

Output:

![image](https://user-images.githubusercontent.com/65585002/120123274-e4481700-c17b-11eb-980f-1fdb9ee56267.png)


### Drawing a 70° circle with a radius of 70px, rotated clockwise 20° with red background


```javascript
const xCoordinate = 100;
const yCoordinate = 100;
selected.fromAngle(xCoordinate, yCoordinate, 70, 20, 70, {
    fill:"red"
});
```

Output:

![image](https://user-images.githubusercontent.com/65585002/120123281-f0cc6f80-c17b-11eb-8877-8c4b18e6846d.png)


View the full capabilities of ArcherJS over at [documentation/Documentation.md]()

## Browser Support

Supported across nearly **all** browsers, including IE and on mobile:

| Chrome | Edge | Firefox | Internet Explorer | Opera | Safari |
| ------ | ---- | ------- | ----------------- | ----- | ------ | 
| 1.0 | 12.0 | 2.0 | 9.0 | 12.1 | 3.1 | 

If your browser supports [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API), it supports ArcherJS. 

## Import

ArcherJS is available through JsDevlir CDN. Add this to the `<head>` tag of your document:

```html
<script src="https://cdn.jsdelivr.net/gh/ColonelParrot/ArcherJS@main/src/ArcherJS.min.js"></script>
```

## Demo

Capability demo here: https://colonelparrot.github.io/ArcherJS/demo.html
