Pysa Documents

========
## Edit 
Our document is writed by Markdown so you can edit it by Mou or anyother Markdown Editor.
#### Document File
  `source/index.md`
#### Attatch Image
  Put image in source/img folder or upload it to Amazon S3
#### Put it Online
  When you accomplish your edit work you must Build and Deploy it to make it effect

## Theme
You can customise your theme base on the init theme

1. `cp -a ./themes/init ./themes/yourthemename`
2. Edit the CSS or HTML,  Add image in the static folder
3. Set `html_theme = 'yourthemename'` in conf.py


## Build
Just run `make` command in project root folder. Then the document will build to `_build/html` folder and you must test it before deploy


## Deploy
Run `make deploy` to deploy project on [ReadTheDocs](http://madeira-cloud-pysa-document.readthedocs.org/en/latest/)

## Changelog

- 2013-10-15 First Release.

## Links

- [Pysa Project Page](http://visualops.github.io/pysa/)
- [Document on ReadtheDocs](http://madeira-cloud-pysa-document.readthedocs.org/en/latest/)
