# proxy-man

Create [PAC] files on demand.

A HTTP request like: `/?.*\.example.com=10.10.10.11` will create a PAC file that sends all traffic
for hosts matching the regexp `.*\.example.com` to the proxy at `10.10.10.11`.

[PAC]: https://en.wikipedia.org/wiki/Proxy_auto-config
