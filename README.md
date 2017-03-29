# destroy-dns

Destroy DNS Route53 record

## Role Variables

* `dns.zone`   : The DNS zone to modify
* `dns.record` : The full DNS record to create
* `dns.type`   : The type of DNS record to create (Choices: A, CNAME, MX, AAAA, TXT, PTR, SRV, SPF, NS, SOA)


## Example playbook
```yaml
- hosts: localhost
  connection: local
  gather_facts: no
  roles:
    - destroy-dns
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigmadigital.com)
