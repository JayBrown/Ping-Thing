# Ping Thing

**SwiftBar/BitBar plug-in to ping servers and display the average round-trip**

## Requisite
* **gtimeout** – install e.g. together with the **coreutils** (using e.g. Homebrew)

## Functionality
* Modes: absolute (current value) / relative (difference between current and previous value)
* Default server: 1.1.1.1
* Optional servers: 1.0.0.1, 1.1.1.1, 149.112.112.112, 8.8.4.4, 8.8.8.8, 9.9.9.9, cloudflare-dns.com, dns.google.com, dns.quad9.net
* Options: switch server / add server / remove server (except default)
* Other options: open plug-in in editor / manual refresh / reset plug-in

![snap1](https://raw.githubusercontent.com/JayBrown/Ping-Thing/main/img/snap1.jpg)

## Files created
* `~/Library/Preferences/local.lcars.PingThing.plist`
* `~/Library/Application Support/local.lcars.PingThing`
