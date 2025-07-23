# Rest Api Symfony Application
========================

Requirements
------------

  * PHP 7.1.3 or higher;
  * PDO-pgSQL PHP extension enabled;
  * Redis;
  * and the [usual Symfony application requirements][1].

Installation
------------

Execute this command to install the project:

Database create and migration
-----------------------------
```bash
$ php bin/console doctrine:database:create
$ php bin/console doctrine:migrations:diff
$ php bin/console doctrine:migrations:migrate
```

Usage
-----

There's no need to configure anything to run the application. Just execute this
command to run the built-in web server and access the application in your
browser at <http://localhost:8000>:

```bash
$ php bin/console server:run
```

Alternatively, you can [configure a fully-featured web server][2] like Nginx
or Apache to run the application.
