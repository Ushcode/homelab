# Iqbal Home Server

Central repository to keep track of everything related to Luke and Oisín's home server.

```text
Host Name: `iqbal`
domain: `iqbal.io`
network ip address: `192.168.0.66`
```



## Future Plans

1. Plex Server
    - Plex
    - Sonarr radarr etc
2. PiHole
3. nextCloud or trueNAS
4. ...



## To Do
1. DNS:
    - Install a DNS Server on your Network
    - Configure the DNS Server to do recursive lookups
    - Configure the DNS Server to host your desired domain(s)
    - Enter the hostname to ip address mappings on the DNS Server
    - Configured your DHCP Server to distribute your DNS Server address out
    - If you find adding each service by hand tedious, take a look at wildcard CNAME and A records. None of the usual security concerns are valid if you run a reverse proxy.
    - DHCP search domains allow completing long subdomains during DNS lookups, so something like https://pihole/ in the URL bar would be resolved to https://pihole.hostname.domain if the search domain is hostname.domain