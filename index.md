# API Platform documentation

## Tutorial

1. [Introduction](tutorial/index.md)
1. [Creating a Fully Featured API in 5 Minutes](tutorial/api.md)
2. [Consuming the API with AngularJS](tutorial/api.md)

## API Platform Core: create a powerful APIs with ease

1. [Introduction](core/introduction.md)
2. [Getting Started](core/getting-started.md)
  1. [Installing API Platform Core](core/getting-started.md#installing-api-platform-core)
  2. [Before Reading this Documentation](core/getting-started.md#before-reading-this-documentation)
  3. [Mapping the Entities](core/getting-started.md#mapping-the-entities)
3. [Operations](core/operations.md)
  1. [Enabling and Disabling Operations](core/operations.md#enabling-and-disabling-operations)
  1. [Configuring Operations](core/operations.md#configuring-operations)
  2. [Creating Custom Operations and Controllers](core/operations.md#creating-custom-operations-and-controllers)
4. [Filters](core/filters.md)
  1. [Search Filter](core/filters.md#search-filter)
  2. [Date Filter](core/filters.md#date-filter)
    1. [Managing `null` Values](core/filters.md#managing-null-values)
  3. [Boolean Filter](core/filters.md#boolean-filter)
  4. [Numeric Filter](core/filters.md#numeric-filter)
  5. [Order filter](core/filters.md#order-filter)
    1. [Using a Custom Order Query Parameter Name](core/filters.md#using-a-custom-order-query-parameter-name)
  6. [Filtering on Nested Properties](core/filters.md#filtering-on-nested-properties)
  7. [Enabling a Filter for All Properties of a Resource](core/filters.md#enabling-a-filter-for-all-properties-of-a-resource)
  8. [Creating Custom Filters](core/filters.md#creating-custom-filters)
    1. [Creating Custom Doctrine ORM Filters](core/filters.md#creating-custom-doctrine-orm-filters)
    2. [Overriding Extraction of Properties from the Request](core/filters.md#overriding-extraction-of-properties-from-the-request)
5. [Serialization Groups and Relations](core/serialization-groups-and-relations.md)
  1. [Configuration](core/serialization-groups-and-relations.md#configuration)
  2. [Using Different Serialization Groups per Operation](core/serialization-groups-and-relations.md#embedding-relations)
  3. [Embedding Relations](core/serialization-groups-and-relations.md#embedding-relations)
    1. [Normalization](core/serialization-groups-and-relations.md#normalization)
    2. [Denormalization](core/serialization-groups-and-relations.md#denormalization)
  4. [Name Conversion](core/serialization-groups-and-relations.md#name-conversion)
  5. [Entity Identifier Case](core/serialization-groups-and-relations.md#entity-identifier-case)
  6. [Writable Entity Identifier](core/serialization-groups-and-relations.md#writable-entity-identifier)
  7. [Embedding the Context](core/serialization-groups-and-relations.md#embedding-the-context)
6. [Validation](core/validation.md)
  1. [Using Validation Groups](core/validation.md#using-validation-groups)
  1. [Dynamic Validation Groups](core/validation.md#dynamic-validation-groups)
7. [Pagination](core/pagination.md)
  1. [Disabling the Pagination](core/pagination.md#disabling-the-pagination)
  2. [Changing the Number of Items per Page](core/pagination.md#changing-the-number-of-items-per-page)
8. [The Event System](core/events.md)
9. [Content Negotiation](core/content-negotiation.md)
  1. [Enabling Several Formats](core/content-negotiation.md#enabling-several-formats)
  2. [Registering a Custom Serializer](core/content-negotiation.md#registering-a-custom-serializer)
  3. [Creating a Responder](core/content-negotiation.md#creating-a-responder)
10. [Using External JSON-LD Vocabularies](core/external-vocabularies.md)
11. [Data Providers](core/data-providers.md)
  1. [Custom Collection Data Provider](core/data-providers.md#creating-a-custom-data-provider#custom-collection-data-provider)
  2. [Custom Item Data Provider](core/data-providers.md#returning-a-paged-collection#custom-item-data-provider)
12. [Security](core/security.md)
13. [Performance](core/performance.md)
  1. [Enabling the Metadata Cache](core/performance.md#enabling-the-metadata-cache)
  2. [Using PPM (PHP-PM)](core/performance.md#using-ppm-php-pm)
14. [Path Naming Strategy](core/path-naming-strategy.md)
  1. [Configuration](core/path-naming-strategy.md#configuration)
  2. [Create a Custom Path Generator](core/path-naming-strategy.md#create-a-custom-path-generator)
    1. [Defining the Resource Path Generator](core/path-naming-strategy.md#defining-the-resource-path-generator)
    2. [Registering the Service](core/path-naming-strategy.md#registering-the-service)
    3. [Configure it](core/path-naming-strategy.md#configure-it)
15. [Configuration Reference](core/configuration.md)
16. [NelmioApiDocBundle Integration](core/nelmio-api-doc.md)
17. [FOSUserBundle Integration](core/fosuser-bundle.md#fosuser-bundle-integration)
  1. [Creating a `User` Entity with Serialization Groups](core/fosuser-bundle.md#creating-a-user-entity-with-serialization-groups)
18. [AngularJS Integration](core/angularjs-integration.md)
  1. [Restangular](core/angularjs-integration.md#restangular)
  2. [ng-admin](core/angularjs-integration.md#ng-admin)

## Schema Generator

1. [Introduction](schema-generator/index.md)
2. [Getting Started](schema-generator/getting-started.md)
3. [Configuration](schema-generator/configuration.md)

## Deployment

1. [Introduction](deployment/index.md)
2. [Deploying an API Platform App on Heroku](deployment/heroku.md)
3. [Using API Platform with Docker](deployment/docker.md)

## Contributing

1. [Contribution guide](https://github.com/api-platform/api-platform/blob/master/CONTRIBUTING.md)
2. [Contributor Code Of Conduct](conduct.md)
