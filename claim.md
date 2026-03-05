# Claim Subdomain

```bash
curl -s -X POST https://plop.so/api/claim \
  -H "Authorization: Bearer $TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"username":"myname"}'
```

Creates `myname.plop.so`. Username: 3-30 chars, lowercase alphanumeric + hyphens.
