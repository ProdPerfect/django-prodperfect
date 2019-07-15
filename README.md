# django-prodperfect
Django template tags for the ProdPerfect tracking snippet.


## Installation
1. `pip install django-prodperfect`
2. Add to `INSTALLED_APPS` in your `settings.py`
    
    `prodperfect,`
3. In your templates, load `prodperfect`

## Example template
```djangotemplate
{% load prodperfect %}


<body>
    ...
    {% tracking_snippet %}
</body>
```


## Bugs and suggestions

If you have found a bug or if you have a request for additional functionality, please use the issue tracker on GitHub.

https://github.com/prodperfect/django-prodperfect/issues


## Author
Developed and maintained by [prodperfect](https://prodperfect.com/).