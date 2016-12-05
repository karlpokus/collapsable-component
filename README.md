# collapsable-component
Click to toggle data in collapsable list. Depends on jQuery.

# usage
```javascript
// keys for nested objects will be rendered as collapsables. Other values are ignored and rendered as a list item.
var data = {
  'Quality': {
    'increase quality': {
      'tomorrow' : null
    }
  },
  'Efficiancy': {
    'be faster': null
  },
  'Delivery': null
};
// constructor(Object, rootElementId)
// rootElementId needs to be present in the DOM
var collapsable = new Collapsable(data, 'root');
```

# demo
[demo](http://codepen.io/KarlPokus/pen/zoZgqX?editors=0010) with some optional styling.

# TODOs
- [x] pass obj as data
- [x] only add icon on collapsables
- [x] moar component style
- [ ] option to set some styling
- [ ] remove jQuery and add some vue.js magic?

# licence
MIT
