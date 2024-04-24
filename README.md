# Iqbal Home Server

Central repository to keep track of everything related to Luke and Oisín's home server.

```text
Host Name: `iqbal`
domain: `iqbal.io`
network ip address: `192.168.0.66`
```

<img width="1327" alt="Screenshot 2024-04-24 at 23 56 28" src="https://github.com/Ushcode/homelab/assets/102725207/759f078a-36ef-4cac-a97e-c99d17e09972">


## Future Plans

1. nextCloud or trueNAS
2. ...



## To Do
1. DNS:
    - Install a DNS Server on the Network
    - Configure the DNS Server to do recursive lookups
    - Configure the DNS Server to host my domain(s)
    - Enter the hostname to ip address mappings on the DNS Server
    - Configured your DHCP Server to distribute your DNS Server address out
    - If you find adding each service by hand tedious, take a look at wildcard CNAME and A records. None of the usual security concerns are valid if you run a reverse proxy.
    - DHCP search domains allow completing long subdomains during DNS lookups, so something like https://pihole/ in the URL bar would be resolved to https://pihole.hostname.domain if the search domain is hostname.domain
