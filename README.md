# Lumol website

This website use [cactus](https://github.com/koenbok/Cactus) as static website
generator. To build it locally, you have to install the dependencies:

```
pip install [--user] cactus pygments
```

And then start the local server:
```
cd src
cactus serve
```

The `http://127.0.0.1:8000` URL now point on a local version of this site.
