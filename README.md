# admin_styles
Styles for the drupal backend and other admin ui elements.

## How to include it in your Drupal project
Add the repository to your composer.json like this:
```json
"repositories": [
  {
      "type": "composer",
      "url": "https://packages.drupal.org/8"
  },
  {
    "type": "git",
    "url": "https://github.com/progressive-digital/admin_styles.git"
  }
]
```

And then require this module:
```bash
composer require 'progressive-digital/admin_styles:^1.0'
```
