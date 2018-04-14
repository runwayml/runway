# Contributing

The Runway app is built using the [electron-react-boilerplate](https://github.com/chentsulin/electron-react-boilerplate)

> [Electron](http://electron.atom.io/) application boilerplate based on [React](https://facebook.github.io/react/), [Redux](https://github.com/reactjs/redux), [React Router](https://github.com/reactjs/react-router), [Webpack](http://webpack.github.io/docs/), [React Transform HMR](https://github.com/gaearon/react-transform-hmr) for rapid application development.


SSL issues, just compile with CPP flags
```
sudo CPPFLAGS=-I/usr/local/opt/openssl/include LDFLAGS=-L/usr/local/opt/openssl/lib yarn add --dev electron-rebuild
```

## Packaging

```bash
sudo yarn package 
```