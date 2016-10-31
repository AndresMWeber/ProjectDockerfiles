# Supported tags

- `PyQt4` `PyQt5`


# Usage

To use this image and any of it's supported tags, use `docker run`.

```bash
$ docker run -ti --rm daemonecles/ubuntu16_04_pyqt
```


```bash
$ docker run -ti --rm daemonecles/ubuntu16_04_pyqt:PyQt4
```

Images occupy around **5 gb** of virtual disk space once installed, and about **1.5 gb** of bandwidth to download.

**Example**

This example will show that PyQt4/5 are installed and importable in python

```bash
$ docker run -ti -v $(pwd)/root/workdir --rm daemonecles/ubuntu_16_04_pyqt
$ python
>>> import PyQt5
>>> import PyQt4
$ exit
```

# What's in this image?

This image builds on [pythonbase-ubuntu] which has the following software installed.

- [git](https://git-scm.com/)
- [pip](https://pip.pypa.io/en/stable/)
- [nose](http://nose.readthedocs.org/en/latest/testing.html)

# User Feedback
I don't expect much of this but please leave any notes you want.

### Documentation

Documentation for this image is stored in the [GitHub wiki][1] for this project.

### Issues

If you have any problems with or questions about this image, please contact me through a [GitHub issue][3].

[3]: https://github.com/mottosso/docker-maya/issues

### Contributing

I'm a total mess so please if you see anything that can be cleaned up let me know.  You can always do pull requests or just email me at andresmweber@gmail.com
