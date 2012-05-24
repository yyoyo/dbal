# Doctrine DBAL (Postgres Fork)

Powerful database abstraction layer with many features for database schema introspection, schema management and PDO abstraction.

This fork try to solve various issues with postgresql. see branch 2.2.2-postgres changelog.

to use it with Symfony change your files to:

deps :

```
[doctrine-common]
    git=http://github.com/doctrine/common.git
    version=2.2.2

[doctrine-dbal]
    git=https://github.com/yyoyo/dbal.git
    version=2.2.2-postgres

[doctrine]
    git=http://github.com/doctrine/doctrine2.git
    version=2.2.2
```

deps.lock :

```
doctrine-common 2.2.2
doctrine-dbal 2.2.2-postgres
doctrine 2.2.2
```

This branch is experimental !!!

## More resources:

* [Website](http://www.doctrine-project.org)
* [Documentation](http://www.doctrine-project.org/projects/dbal/current/docs/en)
* [Issue Tracker](http://www.doctrine-project.org/jira/browse/DBAL)
* [Downloads](http://github.com/doctrine/dbal/downloads)
