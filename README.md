Role Name
=========

A simple ansible role to install docker-compose to a specific version.

Role Variables
--------------

```yml
docker_compose_version: "1.7.1"
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - {
            role: emmetog.docker-compose,
            docker_compose_version: "1.7.1"
         }

License
-------

MIT

Author Information
------------------

Made with love by Emmet O'Grady.

I am the founder of [NimbleCI](https://nimbleci.com) which builds Docker containers for feature branch workflow projects in Github.

I blog on my [personal blog](blog.emmetogrady.com) and on the [NimbleCI blog](blog.nimbleci.com).
