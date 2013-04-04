##Django CMS Facebook Album Plugin

This plugin lets you show the images from a Facebook Album. It presents images in a thumbnail and in colorbox when clicked over.


In order to use this plugin, insert this in your base.py
```py
INSTALLED_APPS = {
  {project}.apps.django-cms-fbalbum
}
```

Add the app files in your apps directory of your project

```
__project
  |__manage.py
  |__requirement.txt
  |__gondor.yml
  |__project\
           |
           |__apps\
                  |__django-cms-fbalbum
```

Then go the the Django CMS Admin panel and add this plugin at your desired placeholder.
