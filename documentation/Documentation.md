# ArcherJS Documentation

## Methods

### `.fromAngle()`

Parameters: (cx, cy, radius, origin, degree, options, counterclockwise):

Draws a portion of a circle based on the degree

- `cx` - x coordinate
- `cy` - y coordinate
- `radius` - radius of the circle
- `origin` - circle rotation angle
- `degree` - degree of circle, 360 for full circle, 180 for half
- `options` - options, described in next section
- `counterclockwise` - direction, default to false

### `.circle()`

Draws a full circle

Parameters: (cx, cy, radius, options):

- `cx` - x coordinate
- `cy` - y coordinate
- `radius` - radius of the circle
- `options` - options, described in next section

### `.semi()`

Draws a semicircle

Parameters: (cx, cy, radius, origin, options, counterclockwise)

- `cx` - x coordinate
- `cy` - y coordinate
- `radius` - radius of the semicircle
- `origin` - semicircle rotation angle
- `options` - options, described in next section
- `counterclockwise` - direction, default to false

### `.quarter()`

Draws a quarter of a circle

Parameters: (cx, cy, radius, origin, options, counterclockwise)

- `cx` - x coordinate
- `cy` - y coordinate
- `radius` - radius of the semicircle
- `origin` - semicircle rotation angle
- `options` - options, described in next section
- `counterclockwise` - direction, default to false

## Options

The `options` parameter is existent in all methods - it accepts an object and supports the following keys:

`fill` : The fill style of the circle

`strokeStyle` : The strokeStyle of the circle

`lineWidth` : The lineWidth of the circle, in `px`

An example Options JSON object would be:

```javascript
{
    fill:"red",
    strokeStyle:"blue",
    lineWidth:"10"
}
```

If you do not wish to provide any options, you can simply pass `null`, which is more time-efficient than passing an empty JSON (`{}`).
