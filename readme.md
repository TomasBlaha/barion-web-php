# Barion PHP SDK with Composer support

Barion PHP SDK with added Composer support.
Repository is currently WIP, there is a list of thing to accomplish before stable release:

- Add Namespaces
- Refactor Enumerations, Constants etc.
- Add PSR-4 autoloading compatibility
- Create Symfony bundle out of the SDK

Currently, autoloading can be achieved using Composer's classmap:

```
"autoload": {
    "classmap": [
        "vendor/tomas-blaha/barion-web-php/library"
    ]
}
```
