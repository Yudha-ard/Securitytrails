### Subdomain Enum

Hapus {} ganti sesuai value nya
```
curl -XPOST 'https://api.securitytrails.com/v1/domains/list?include_ips=false&page=1&scroll=true' -H 'apikey: {api_key}' -d '{"query":"apex_domain = '\''{domain}'\''"}'
````
