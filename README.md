jQuery-Plugin-Boilerplate
=========================

## Usage test
``` 
$('.some-element').jqueryPlugin({
    defaultOption: 'Overwrite some default option',
    onEventCallback: function(data) {
        console.log('onEventCallback:', data);
    }
});

console.log($('.some-element').jqueryPlugin('someGetterMethod'));
```
