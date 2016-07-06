Role Name
=========

A simple ansible role to install docker-compose to a specific version.

Role Variables
--------------

```yml
docker_compose_version: "1.7.1"
```

Usage
-----

First install the role from ansible galaxy:
```
$ ansible-galaxy install emmetog.docker-compose
```

Then use the role in a playbook as follows:
```yml
- hosts: servers
  roles:
     - {
        role: emmetog.docker-compose,
        docker_compose_version: "1.7.1"
     }
```

License
-------

MIT

Author Information
------------------

Made with love by Emmet O'Grady.

I am the founder of [NimbleCI](https://nimbleci.com) which builds Docker containers for feature branch workflow projects in Github.

I blog on my [personal blog](http://blog.emmetogrady.com) and about Docker related things on the [NimbleCI blog](http://blog.nimbleci.com).
