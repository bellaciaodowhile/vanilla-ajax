# vanilla-ajax
Esta es una función que te permite hacer peticiones AJAX mediante XMLHttpRequest.
### Su uso es simple, enviando datos:
```
AJAXGJ8({
    url: 'Home/dashboard',
    data: [{
        name: 'name',
        surname: 'Surname'
    }],
    success: function(res) {
        console.log(res)
    },
    error: function(res) {
        console.error(res)
    }
});

```
### Su uso es simple, solo recibiendo datos:
```
AJAXGJ8({
    url: 'Home/dashboard',
    success: function(res) {
        console.log(res)
    },
    error: function(res) {
        console.error(res)
    }
});

```
