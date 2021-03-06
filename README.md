README
================

Requirements
------------

The supported Magento version is 1.9.x

Features
----------------

- ajax navigation using history pushState/popState
- price slider with submit button
- SEO URLs (http://www.example.com/men/shirts/filter/fit/regular,sharp/sleeve_length/long-sleeve.html)
- multiple filters for the same attribute

All the above features can be enabled/disabled from backend: "System -> Configuration -> Catalin SEO -> Catalog Layered Navigation"

Install via Modman
----------------

You can install this module using [Colin Mollenhour's](https://github.com/colinmollenhour) [Modman tool](https://github.com/colinmollenhour/modman).

```bash
$ modman init
$ modman clone https://github.com/roman204/improved-magento-layered-navigation.git
```

Install via composer
--------------------

You can install this module using [Magento Hackathon Team](https://github.com/magento-hackathon/magento-composer-installer)
```
{
    "require": {
        "multibyte/improved_magento_layered_navigation": "1.1"
    }
}
```
