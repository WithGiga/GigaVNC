## noVNC: HTML VNC client library and application

[![Test Status](https://github.com/novnc/noVNC/workflows/Test/badge.svg)](https://github.com/novnc/noVNC/actions?query=workflow%3ATest)
[![Lint Status](https://github.com/novnc/noVNC/workflows/Lint/badge.svg)](https://github.com/novnc/noVNC/actions?query=workflow%3ALint)

### Screenshots

Running in Firefox before and after connecting:

<img src="http://novnc.com/img/noVNC-1-login.png" width=400>&nbsp;
<img src="http://novnc.com/img/noVNC-3-connected.png" width=400>

### Description

noVNC is a HTML VNC client JavaScript library and application that runs in any modern browser including mobile (iOS, Android). Used by OpenStack, OpenNebula, and many other projects.

### Quick Start

**Basic usage:**
```bash
./utils/novnc_proxy --vnc localhost:5901
```

**Local only:**
```bash
./utils/novnc_proxy --vnc localhost:5901 --listen localhost:6081
```

**Snap package:**
```bash
sudo snap install novnc
novnc --listen 6081 --vnc localhost:5901
```

Point your browser to the URL output by the script, click Connect, and enjoy!

### Features

* All modern browsers including mobile
* Multiple authentication methods (VNC, RSA-AES, Tight, VeNCrypt, etc.)
* Multiple encodings (raw, tight, ZRLE, H.264, etc.)
* Scaling, clipping, resizing
* Mouse buttons, local cursor, clipboard support
* Touch gestures, translations
* [MPL 2.0](LICENSE.txt) licensed

### Requirements

**Browsers:** Chrome 89+, Firefox 89+, Safari 15+, Opera 75+, Edge 89+

**Server:** VNC server with WebSockets support or use [websockify](https://github.com/novnc/websockify) proxy

### Documentation

* [Embedding](docs/EMBEDDING.md) - Application integration
* [Library](docs/LIBRARY.md) - JavaScript library usage
* [API](docs/API.md) - API documentation

### Support

* Website: [novnc.com](http://novnc.com)
* Discussion: [Google Groups](https://groups.google.com/forum/?fromgroups#!forum/novnc)
* Issues: [GitHub Issues](https://github.com/novnc/noVNC/issues)
* Wiki: [GitHub Wiki](https://github.com/novnc/noVNC/wiki/)

### Contributing

See [AUTHORS](AUTHORS) for contributors. Check out issues marked ["patchwelcome"](https://github.com/novnc/noVNC/issues?labels=patchwelcome) and our [contribution guide](https://github.com/novnc/noVNC/wiki/Contributing).
