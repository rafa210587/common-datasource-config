# DataSource Config for autoconfigure the connection to the sql and already built-in GenericJdbcTemplate

#### How to use:
Just add the dependency in your project pom and you can start using with genericJdbcTemplate(no need to instanciate the bean, its already made for you, just use it wisely).

Also add in your application main class the @import({ DataSourceConfig.class })

Also you need to inform the .elsq just add at your .properties the property spring.application.name.
