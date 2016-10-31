# Supported tags

- `centos7` `centos6`


# Usage

To use this image and any of it's supported tags, use `docker run`.

```bash
$ docker run -ti --rm daemonecles/pythonbase-centos
```


```bash
$ docker run -ti --rm daemonecles/pythonbase-centos:centos7
```

Images occupy around **5 gb** of virtual disk space once installed, and about **1.5 gb** of bandwidth to download.

**Example**

This example will show that python 2.7 and 3.5 are installed and importable in python

```bash
$ docker run -ti -v $(pwd)/root/workdir --rm daemonecles/pythonbase-centos
$ python2.7
>>> exit()
$ python3.5
>>> exit()
$ exit
```

# What's in this image?

This image builds on [centos] and this image has the following software installed.

- [git](https://git-scm.com/)
- [pip](https://pip.pypa.io/en/stable/)
- [nose](http://nose.readthedocs.org/en/latest/testing.html)

# User Feedback
I don't expect much of this but please leave any notes you want.

### Documentation

Documentation for this image is stored in the [GitHub wiki][1] for this project.

### Contributing

I'm a total mess so please if you see anything that can be cleaned up let me know.  You can always do pull requests or just email me at andresmweber@gmail.com
