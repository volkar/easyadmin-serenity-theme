# EasyAdmin Serenity theme

*EasyAdmin is an administration backends for Symfony applications.*

## Preview
Dark version:
![EasyAdmin Serenity dark theme](https://github.com/volkar/easyadmin-serenity-theme/blob/main/preview/serenity-preview-dark.jpg?raw=true)

Light version:
![EasyAdmin Serenity light theme](https://github.com/volkar/easyadmin-serenity-theme/blob/main/preview/serenity-preview-light.jpg?raw=true)

## Installation
You can include this theme in AdminDashboardController.php:
```php
public function configureAssets(): Assets
{
    return parent::configureAssets()->addCssFile('static/easyadmin_serenity_theme.css');
}
```
There is also [theme for SonataAdmin](https://github.com/volkar/sonataadmin-nightshade-theme) with this colors.

## Contact me

You always welcome to mail me at sergey@volkar.ru
