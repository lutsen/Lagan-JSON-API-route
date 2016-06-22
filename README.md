[<img src="https://cdn.rawgit.com/lutsen/lagan/master/lagan-logo.svg" width="100" alt="Lagan">](https://github.com/lutsen/lagan)

Lagan JSON API routes
=====================

Route file to be used with Lagan to create a JSON API.

To install, add *api.php* to the *routes* directory. To protect the */api/write* route, add it to the Slim HTTP Basic Authentication middleware setup in the Lagan index.php file:
`'path' => ['/admin', '/api/write']`.

To be used with [Lagan](https://github.com/lutsen/lagan). Lagan lets you create flexible content objects with a simple class, and manage them with a web interface.

Lagan is a project of [Lútsen Stellingwerff](http://lutsen.land/) from [HoverKraft](http://www.hoverkraft.nl/).