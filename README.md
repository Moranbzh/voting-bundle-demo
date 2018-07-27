Symfony Demo Application for MsalsasVotingBundle
================================================

This is a demo for [MsalsasVotingBundle](https://github.com/msalsas/MsalsasVotingBundle).
 
Cloned from [Symfony Demo Application](https://github.com/symfony/demo).

Requirements
------------

  * PHP 7.1.3 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements][1].

Installation
------------

Execute this command to install the project:

```bash
$ git clone https://github.com/msalsas/voting-bundle-demo.git
$ cd voting-bundle-demo/
$ composr install
```

Usage
-----

There's no need to configure anything to run the application. Just execute this
command to run the built-in web server and access the application in your
browser at <http://localhost:8000>:

```bash
$ cd voting-bundle-demo/
$ php bin/console server:run
```

Alternatively, you can [configure a fully-featured web server][2] like Nginx
or Apache to run the application.


[1]: https://symfony.com/doc/current/reference/requirements.html
[2]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
