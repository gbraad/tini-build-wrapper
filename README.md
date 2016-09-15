Tini build wrapper
==================

Build wrapper for [tini](https://github.com/krallin/tini), an init replacement


Usage
-----

### CentOS/Fedora
Download the [tini.repo](http://gbraad.gitlab.io/tini/tini.repo) file and place it in `/etc/yum.repos.d`.

```
$ wget http://gbraad.gitlab.io/tini/tini.repo -O /etc/yum.repos.d/tini.repo
$ yum install -y tini
```

```
$ wget http://gbraad.gitlab.io/tini/tini/tini_0.10.0.rpm
$ rpm -ivh tini_0.10.0.rpm
```


### Debian/Ubuntu

```
$ add-apt-repository 'deb http://gbraad.gitlab.io/tini/ tini main'
$ apt-get update
$ apt-get install -y tini
```

```
$ wget http://gbraad.gitlab.io/tini/tini_0.10.0.deb
$ dpkg -i tini_0.10.0.deb
```


Thanks
------

  * Thomas Orozco, for creating [tini](https://github.com/krallin/tini)
  * [GitLab](https://gitlab.com/) for providing a great infrastructure



Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad)  |

