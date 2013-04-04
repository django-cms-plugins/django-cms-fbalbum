##Django CMS Facebook Album Plugin

Django CMS provides a great way to create websites. There are lots of plugin available for it.

This plugin lets you show the images from a Facebook Album. It presents images in a thumbnail and uses Jquery colorbox when clicked on it.

In order to use this plugin follow these steps:

- Add the files in the static subdirectory of the app to the main static directory of the app.

- insert this in your base.py
```py
INSTALLED_APPS = {
  {project}.apps.django-cms-fbalbum
}
```

- Add the app files in your apps directory of your project

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

After that, click on the plugin and enter the Facebook Album URL in the placeholder. Then save and reload your website.
