# Personal DNS zone file configuration

This repository contains zone file configuration for all domains owned by
remission.org.uk

## DNS zone files

A Domain Name System (DNS) zone file is a text file that describes a DNS zone.
A DNS zone is a subset, often a single domain, of the hierarchical domain name
structure of the DNS. The zone file contains mappings between domain names and
IP addresses and other resources, organized in the form of text representations
of resource records (RR). A zone file may be either a DNS master file,
authoritatively describing a zone, or it may be used to list the contents of a
DNS cache

## File Format

Bytemark uses [tinydns-data](http://cr.yp.to/djbdns/tinydns-data.html) format
to describe DNS zone file configuration.

## Domains

Each domain zone file is named as follows -

```
data/domain.co.uk.txt
data/domain.org.uk.txt
```

Domains transferred to Bytemark -

* jesuslovesamerika.co.uk

Domains to be transferred from freeparking.co.uk -

* remission.org.uk
* cheyney.me.uk

## Transfer domain to Bytemark

See [Bytemark documentation](https://www.bytemark.co.uk/docs/domains/dnsc/).
