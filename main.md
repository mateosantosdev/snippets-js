### Find the max value in an array:
`Math.max(...array)`

### Remove duplicates from an array:
`[...new Set(array)]` 

### Get the current date and time:
`new Date().toString()`

### Convert an object to an array:
`Object.values(object)`

### Count the occurrences of an element in an array:
`array.filter(x => x === element).length`

### Create a new object with a dynamic key and value:
`{ [key]: value }`

### Mock window.location in unit tests
```
beforeEach(() => {
 const urlparams = `firstparam=thisismyfirstparamvalue`;
 window.history.pushState({}, 'Page title while testing', `/myurl/with/params?${search}`);
});
```

### Hide promoted jobs in Linkedin
```
javascript:var i=0,x=document.getElementsByClassName('jobs-search-results-list')[0];function phase2(){document.querySelectorAll("li").forEach(function(e){e.id&&e.innerHTML.match(/Promoted/)&&e.remove()}),setTimeout(function(){x.scrollTop=0},0)}!function e(){x.scroll(0,100*++i),i>40?phase2():setTimeout(e,0)}();
```
