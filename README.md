Symfony bundle for wizards/php-rest-api

# Install
```
composer require wizards/rest-bundle
```

Register it in your AppKernel
```
new Bigz\HalapiBundle\BigzHalapiBundle(),
```

# Usage
It provides a subscriber to serialize your responses to jsonapi, and
a paramconverter to inject psr7 requests

# Further Documentation
Have a look at http://github.com/wizardstechnologies/php-rest-api

# TODO
- (MUST) Provide configuration options to use the implementation of your choiche (ORM, ODM, ...)
