# Paragon Admin Experience Recipe
This is a Drupal Composer recipe that provides a streamlined and opinionated admin experience setup for Drupal 10/11 projects. It includes essential modules, configuration, and optional development tools to improve the site-building and content authoring experience.

## Requirements
- Drupal 10.0 or later (Drupal 11 supported)
- Composer 2.x
- PHP 8.1 or higher

## Installation
To use this recipe in your Drupal project:

1. Add the VCS repository reference to your project's `composer.json`:
```json
"repositories": [
  {
    "type": "vcs",
    "url": "https://github.com/elevatedthird/paragon-admin-experience-recipe"
  }
]
```

2. Require the recipe via Composer:
```bash
composer require drupal_recipe/paragon_admin_experience_recipe:^1.0
```

## What’s Included
- Core configuration for the admin UI
- Recommended contrib modules for improved authoring
- Development and UX enhancements
- Optional packages may include:
  - environment_indicator
  - environment_indicator_ui
  - gin
  - gin_lb
  - gin_lb_plus
  - gin_toolbar
  - inline_block_title_automatic
  - kinetic_extras
  - navigation
  - layout_builder
  - layout_builder_browser
  - layout_builder_operation_link
  - layout_discovery
  - section_library
  - 
## Updating
When a new release is available:

```bash
composer update drupal_recipe/paragon_admin_experience_recipe
```

## How to run
```bash 
recipe ../recipes/paragon_admin_experience_recipe
```


## License

[MIT](LICENSE)
