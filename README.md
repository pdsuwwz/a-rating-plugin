# About this Rating Plugin Based on jQuery

#### Basic info

* A rating plug-in that can customize icons to create a variety of rating combinations, the number of stars.


#### Usage

> To introduce css and javascript files into the page.

`<link rel="stylesheet" type="text/css" href="./css/style.css">`

`<script type="text/javascript" src="./js/jquery.rating.js"></script>`

> You just need to have a ul to build Rating.

```css
<ul class="rating" id="rating1">
  <li class="rating-item" title="很不好"></li>
  <li class="rating-item" title="不好"></li>
  <li class="rating-item" title="一般"></li>
  <li class="rating-item" title="好"></li>
  <li class="rating-item" title="很好"></li>   
</ul>
```

#### Score

`$("#rating1").rating(num);`

param | Type | Description 
- | :-: | -: 
num | {Number} | the number of stars 

#### Update Log