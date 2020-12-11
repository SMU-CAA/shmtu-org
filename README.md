# SHMTU ORG

> 🌈 To get a subdomain for your own site. Pull request welcome.

## Usage

Just append lines to `dns_records.yml` file as follows:

```yaml
  - name: sub
    description: example
    type: A
    value: 1.1.1.1
    ttl: 1
    proxied: false
```

## Options

- `type`
  - `A`
  - `AAAA`
  - `CNAME` (default)

- `ttl`
  - `1` (default)
  - `120`
  - `300`
  - `600`
  - `1800`
  - `3600`

- `proxied` by [cloudflare](https://www.cloudflare.com/zh-cn/)
  - `true`
  - `false` (default)

## Notes

You are not able to access your website if your server is in Mainland China because of a lack of ICP license.
