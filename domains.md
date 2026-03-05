# Domains

```bash
# List
curl -s https://plop.so/api/domains -H "Authorization: Bearer $TOKEN"

# Add (returns checkout_url for payment)
curl -s -X POST https://plop.so/api/domains \
  -H "Authorization: Bearer $TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"hostname":"example.com"}'

# Remove
curl -s -X DELETE https://plop.so/api/domains \
  -H "Authorization: Bearer $TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"hostname":"example.com"}'
```
