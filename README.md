# SFM SOCK
A websocket client for Source Filmmaker intended to trasmit scene and frame data to other applications.

This software can be used to transmit scenes from Source Filmmaker with 1:1 accuracy.

## Installation
Merge ``mainmenu`` with ``Source Filmmaker/game/usermod/scripts/mainmenu``.

You should now see the scripts as options in the ``Scripts`` tab in Source Filmmaker.

## Usage
Requires the use of an SFM SOCK-compatible websocket server.

If you are connecting to another websocket client (such as the [SFM SOCK Websocket Client for Garry's Mod](https://github.com/TeamPopplio/sfmsock-wsc-gmod)), you must use a proxy server.

The [SFM SOCK Websocket Server Proxy](https://github.com/TeamPopplio/sfmsock-wss-proxy) is provided for ease of use.

To run the proxy server, you must have [node.js](https://nodejs.org/) v16 or higher installed.

## Connecting to a server
When a server is running, you can connect to it by launching the ``Connect`` script within Source Filmmaker.

The default server IP is ``localhost``, it can be changed via the ``SFMSOCK_TCP_IP`` environment variable.

The default server port is ``9191``, it can be changed via the ``SFMSOCK_TCP_PORT`` environment variable.

Once the client has successfully connected, it will update automatically.

Afterwards, manual updates can be sent through the ``Transmit`` script.

## License
This software is licensed under the MIT License.
