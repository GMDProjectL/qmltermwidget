# QMLTermWidget

## Description
This project is a QML port of qtermwidget. It is written to be as close as possible to the upstream project in order to make cooperation possible.

This plugin will power UniTerminal, terminal emulator for Uni desktop environment.

This package also contains a simple test application.

# Building

```bash
mkdir build && cd build
qmake6 .. && make -j6
```

## Installing

```bash
cd build
sudo make install
```

To test it:

```bash
qmlscene6 -I . test-app/test-app.qml
```
