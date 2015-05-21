# Dokku Extra Domains

Handle multiple domains for a [dokku](https://github.com/progrium/dokku) host.

## Installation

On the Dokku server, install the plugin in the plugins directory and run `dokku plugins-install`:

```
cd /var/lib/dokku/plugins
git clone https://github.com/alessio/dokku-extra-domains extra-domains
dokku plugins-install
```

## Usage

```
Options:
    domains-extra       List all extra domains
```

## Notes

List your extra domains in `/home/dokku/EXTRA_DOMAIN`:
```
root@dokku.me:~# cat /home/dokku/EXTRA_DOMAINS
example.com
domain.tld
anotherdomain.io
```
