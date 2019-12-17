# Symfony-Notes




```

php bin/console cache:clear 

```

```

yarn encore dev

```

```

yarn encore dev --watch

```


```

php app/console  generate:doctrine:form AppBundle:Order\DeliveryParty 

```

```

php app/console  generate:controller AppBundle:Order\Party 

```

```

Options:
  -h, --help               Display this help message
  -q, --quiet              Do not output any message
  -V, --version            Display this application version
      --ansi               Force ANSI output
      --no-ansi            Disable ANSI output
  -n, --no-interaction     Do not ask any interactive question
  -s, --shell              Launch the shell.
      --process-isolation  Launch commands from shell as a separate process.
  -e, --env=ENV            The Environment name. [default: "dev"]
      --no-debug           Switches off debug mode.
  -v|vv|vvv, --verbose     Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

Available commands:
  help                                               Displays help for a command
  list                                               Lists commands
 app
  app:add-product-payment-method                     add product payment method
  app:brand-update                                   update all active product search text
  app:cache-update                                   Update all caches for given legal entity
  app:clear-active-items                             ...
  app:clear-expired-new-items                        ...
  app:cms:mysl:department-page:brand-row             Update department page brand row for mysoftlogic cms
  app:cms:mysl:department-page:trending-product-row  Update department page trending product row for mysoftlogic cms
  app:cms:mysl:subcat-le-update                      Update subcategory legal entity by category
  app:elasticsearch-product-upload                   Upload products to Elastic Search
  app:fix-min-max-order-levels                       ...
  app:fix-product-is-active                          ...
  app:gloamrk:update-product-names                   update all glomark product names from oracle.
  app:gloamrk:update-product-payment-methods         update all glomark product payment methods
  app:glomark:onpromo                                used to update isDeal field in glomark products ...
  app:image:product:optimize                         ...
  app:img-clear-cache                                ...
  app:map-erp-code                                   ...
  app:mysl:exclude-deal-products-from-installments   ...
  app:order:process-automate                         Used to autmate the backend order processing operations ...
  app:price-update                                   This is used to update base price of selected products
  app:product-delivery-restrictions:update           ...
  app:product-details:update                         To update product details(conversion factor, minimum order level, maximum order level)

  app:product-images:update                          ...
  app:product-update-search-index                    update search index of products
  app:product:img:convertpngtojpg                    used to convert product images from png to jpg
  app:product:img:resize                             used to create resize product images
  app:product:oracle:create-new                      This is used to create new products from oracle dump
  app:product:promotion:clear-expired-timer-deal     ...
  app:product:promotion:clone                        ...
  app:product:promotion:remove                       ...
  app:promotion-auto-update                          ...
  app:related-products:update                        Update related products
  app:remove-product-payment-method                  remove product payment method
  app:report:sales-report                            Generate ans send sales report email
  app:search-text-auto-update                        update all active product search text
  app:send-daily-sms                                 Send a sms to given set of user with order summary of current month
  app:set-active-expire-general-promotions           ...
  app:shipping-clone                                 update all active product shipping details
  app:sms-sender                                     Sends an sms with the given to the given number
  app:subscription-auto-update                       Add registered users to subscribed list is they are not in that list
  app:update-product-applicable-price                ...
  app:user:staff_sync                                Sync user type ( staff or not ) from oracle
  app:user:update-api-key                            ...
 assetic
  assetic:dump                                       Dumps all assets to the filesystem
  assetic:watch                                      Dumps assets to the filesystem as their source files are modified
 assets
  assets:install                                     Installs bundles web assets under a public web directory
 cache
  cache:clear                                        Clears the cache
  cache:warmup                                       Warms up an empty cache
 config
  config:debug                                       Dumps the current configuration for an extension
  config:dump-reference                              Dumps the default configuration for an extension
 container
  container:debug                                    Displays current services for an application
 debug
  debug:config                                       Dumps the current configuration for an extension
  debug:container                                    Displays current services for an application
  debug:event-dispatcher                             Displays configured listeners for an application
  debug:router                                       Displays current routes for an application
  debug:swiftmailer                                  Displays current mailers for an application
  debug:translation                                  Displays translation messages information
  debug:twig                                         Shows a list of twig functions, filters, globals and tests
 doctrine
  doctrine:cache:clear                               Flush a given cache
  doctrine:cache:clear-collection-region             Clear a second-level cache collection region.
  doctrine:cache:clear-entity-region                 Clear a second-level cache entity region.
  doctrine:cache:clear-metadata                      Clears all metadata cache for an entity manager
  doctrine:cache:clear-query                         Clears all query cache for an entity manager
  doctrine:cache:clear-query-region                  Clear a second-level cache query region.
  doctrine:cache:clear-result                        Clears result cache for an entity manager
  doctrine:cache:contains                            Check if a cache entry exists
  doctrine:cache:delete                              Delete a cache entry
  doctrine:cache:flush                               Flush a given cache
  doctrine:cache:stats                               Get stats on a given cache provider
  doctrine:database:create                           Creates the configured database
  doctrine:database:drop                             Drops the configured database
  doctrine:database:import                           Import SQL file(s) directly to Database.
  doctrine:ensure-production-settings                Verify that Doctrine is properly configured for a production environment.
  doctrine:generate:crud                             Generates a CRUD based on a Doctrine entity
  doctrine:generate:entities                         Generates entity classes and method stubs from your mapping information
  doctrine:generate:entity                           Generates a new Doctrine entity inside a bundle
  doctrine:generate:form                             Generates a form type class based on a Doctrine entity
  doctrine:mapping:convert                           Convert mapping information between supported formats.
  doctrine:mapping:import                            Imports mapping information from an existing database
  doctrine:mapping:info
  doctrine:query:dql                                 Executes arbitrary DQL directly from the command line.
  doctrine:query:sql                                 Executes arbitrary SQL directly from the command line.
  doctrine:schema:create                             Executes (or dumps) the SQL needed to generate the database schema
  doctrine:schema:drop                               Executes (or dumps) the SQL needed to drop the current database schema
  doctrine:schema:update                             Executes (or dumps) the SQL needed to update the database schema to match the current mapping met
adata.
  doctrine:schema:validate                           Validate the mapping files.
 esub
  esub:email_confirm_expire                          This is used to mark expired email confirm users
 frimi
  frimi:reset-request-id                             Reset request id to 000000
 generate
  generate:bundle                                    Generates a bundle
  generate:command                                   Generates a console command
  generate:controller                                Generates a controller
  generate:doctrine:crud                             Generates a CRUD based on a Doctrine entity
  generate:doctrine:entities                         Generates entity classes and method stubs from your mapping information
  generate:doctrine:entity                           Generates a new Doctrine entity inside a bundle
  generate:doctrine:form                             Generates a form type class based on a Doctrine entity
 lint
  lint:twig                                          Lints a template and outputs encountered errors
  lint:yaml                                          Lints a file and outputs encountered errors
 orm
  orm:convert:mapping                                Convert mapping information between supported formats.
 product
  product:update:main-image                          Update Product Main Image
 router
  router:debug                                       Displays current routes for an application
  router:dump-apache                                 [DEPRECATED] Dumps all routes as Apache rewrite rules
  router:match                                       Helps debug routes by simulating a path info match
 search
  search:brandslist:update                           Update Search Brands List
  search:quicklist:update                            Update Quick Search List
 security
  security:check                                     Checks security issues in your project dependencies
  security:encode-password                           Encodes a password.
 server
  server:run                                         Runs PHP built-in web server
  server:start                                       Starts PHP built-in web server in the background
  server:status                                      Outputs the status of the built-in web server for the given address
  server:stop                                        Stops PHP's built-in web server that was started with the server:start command
 swiftmailer
  swiftmailer:debug                                  Displays current mailers for an application
  swiftmailer:email:send                             Send simple email message
  swiftmailer:spool:send                             Sends emails from the spool
 tinypng
  tinypng:compress                                   Compress images
 translation
  translation:debug                                  Displays translation messages information
  translation:update                                 Updates the translation file
 twig
  twig:debug                                         Shows a list of twig functions, filters, globals and tests
  twig:lint                                          Lints a template and outputs encountered errors
 vich
  vich:mapping:debug                                 Debug a mapping.
  vich:mapping:debug-class                           Debug a class.
  vich:mapping:list-classes                          Searches for uploadable classes.
 yaml
  yaml:lint                                          Lints a file and outputs encountered errors


```
























