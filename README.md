# What is a Tor proxy?

A Tor proxy is a SOCKS5 proxy which routes your traffic through the Tor network. The Tor network ensures that any traffic originating from inside the network gets routed through atleast 3 random relays before exiting through the exit node.

It helps you to anonymize traffic, block trackers and, prevent surveillance amongst other benefits. If you are wondering who should use Tor, the answer is every person who cares about their privacy.

```
docker run --rm --detach --name tor --publish 9050:9050 dev852com/tor-socks5
```

# Browser Configuration

Recommends using Firefox

Settings -> Network Settings -> Settings

![screen-1](https://github.com/dev852com/docker-tor-socks5/blob/main/firefox-tor.png)
