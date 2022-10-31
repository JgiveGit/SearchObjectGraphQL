# Changelog

## Version 1.0.4

* __[feature]__ Added `deprecation_reason` to `option` (@IgrekYY)

## Version 1.0.3

* __[fix]__ Support GraphQL 2.0 gem (@rstankov)

## Version 1.0.2

* __[feature]__ Added `argument_options` to `option` (@wuz)

## Version 1.0.1

* __[fix]__ `camelize` defaults to false when not specified (@haines)

## Version 1.0.0

* __[break]__ Removed support for defining types via `type` method (@rstankov)
* __[break]__ Require `GraphQL::Schema::Resolver` inheritance (@rstankov)
* __[break]__ Removed support for legacy `GraphQL::Function` (@rstankov)
* __[break]__ `type` creates type based on `GraphQL::Schema::Object`, not the deprecated `GraphQL::ObjectType.define` (@rstankov)

## Version 0.3.2

* __[feature]__ Added `camelize` argument to `option`, *`true` by default* (@glenbray)

## Version 0.3.1

* __[fix]__ Support for GraphQL gem version v1.9.16 (@ardinusawan)

## Version 0.3

* __[feature]__ Allow passing `required` key to option definition (@vfonic)
* __[fix]__ Support for GraphQL gem enums (@Postmodum37)

## Version 0.2

* Added support for GraphQL::Schema::Resolver (@rstankov)
* Added support for GraphQL 1.8 class API (@rstankov)

## Version 0.1

* Initial release (@rstankov)
