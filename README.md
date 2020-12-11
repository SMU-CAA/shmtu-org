# SHMTU ORG

> 🌍 To get a subdomain for your own site.

## Usage:

Just append lines to `dns_records.yml` file as follows:

```yaml
  - name: sub
    description: example
    type: A
    value: 1.1.1.1
```

Accepted DNS record types:
- A
- AAAA
- CNAME

🌈 Pull request welcome.

_**Note: No ICP license support in China, so you may not able to access your website if your server's in Mainland China.**_
