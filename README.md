# angular-areaspline [![Build Status](https://secure.travis-ci.org/Venturocket/angular-areaspline.png?branch=master)](http://travis-ci.org/Venturocket/angular-areaspline)
Simple areaspline chart directive. Uses d3's area chart.

## Usage
#### Markup
As an element:
```
<areaspline
	data="{string}"
	width="{float}"
	height="{float}">
</areaspline>
```
As an attribute:
```
<div
	areaspline
	data="{string}"
	width="{float}"
	height="{float}">
</div>
```

#### Parameters
|Param	|Type	|Required|Details|
|-------|-------|--------|-------|
|data	|string	|yes    |Angular expression from which to get the data. Expects an array of numbers, e.g. `[ 1, 2, 3, ...]` |
|transition|boolean |no |If true, an animated transition will be performed when the chart's data is updated.|
|width	|integer |no    |Gets passed directly to the SVG |
|height	|integer |no    |Gets passed directly to the SVG |
