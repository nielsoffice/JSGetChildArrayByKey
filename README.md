# JSGetChildArrayByKey
JavaScript jQuery get children element by it's current key using jQuery method get();

```HTML
<div id="main">
  <div>1</div>  <!-- 0 -->
  <div>2</div>  <!-- 1 -->
  <div>3</div>  <!-- 2 -->
</div>
```

```JS
// let getKey = jQuery('#main').children().eq(1);
let getKey = jQuery('#main').children().get(1);

console.log( getKey );
// result 
// <div>2</div>
```
