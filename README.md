Repository Information
======================
Builds a [Docker] container running [Redis] ready for use. Provisioning provided via [Ansible].

How-To
------
Build
```
docker build -t ansible-redis .
```

Consume

`docker run --name elasticsearch -d mrlesmithjr/redis`

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- [@mrlesmithjr]
- [everythingshouldbevirtual.com]
- [mrlesmithjr@gmail.com]


[Ansible]: <https://www.ansible.com/>
[Docker]: <https://www.docker.com>
[Redis]: <http://redis.io>
[@mrlesmithjr]: <https://twitter.com/mrlesmithjr>
[everythingshouldbevirtual.com]: <http://everythingshouldbevirtual.com>
[mrlesmithjr@gmail.com]: <mailto:mrlesmithjr@gmail.com>
