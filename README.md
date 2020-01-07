
# pywebsocket3 #

The pywebsocket project aims to provide a [WebSocket](https://tools.ietf.org/html/rfc6455) standalone server and a WebSocket extension for [Apache HTTP Server](https://httpd.apache.org/), mod\_pywebsocket.

pywebsocket is intended for **testing** or **experimental** purposes.

Please see [Wiki](../../wiki) for more details.

# INSTALL #

To install this package to the system, run this:
```
$ python setup.py build
$ sudo python setup.py install
```

To install this package as a normal user, run this instead:

```
$ python setup.py build
$ python setup.py install --user
```
# LAUNCH #

To use pywebsocket as Apache module, run this to read the document:
```
$ pydoc mod_pywebsocket
```
To use pywebsocket as standalone server, run this to read the document:
```
$ pydoc mod_pywebsocket.standalone
```
