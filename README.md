# Breadcrumb Plugin for [Fansoro CMS](http://fansoro.org/)

![version](https://img.shields.io/badge/version-1.1.0-brightgreen.svg?style=flat-square "Version")
![Fansoro](https://img.shields.io/badge/Fansoro-2.x-green.svg?style=flat-square "Fansoro Version")
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/pafnuty-fansoro-plugins/fansoro-plugin-breadcrumb/blob/master/LICENSE)

The plugin to create breadcrumbs for site.



## Advantages
- Easy use.
- SEO-frendly template.


## Install
Copy the content of folder `upload` in the root of the site.
If you use custom template copy the folder `/upload/themes/default/plugins/` folder with your template.

## Configuration
- Open `/plugins/breadcrumb/breadcrumb.yml` and configure the settings.
```yml
# List of item's readable text or labels
labels:
  home: Main
```

## Usage
```smarty
{Action::run('breadcrumb')}
```

## License 
[MIT](https://github.com/pafnuty/fansoro-less/blob/master/LICENSE)