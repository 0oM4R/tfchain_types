To generate endpoint file, fetch metadata from the chain using:
```bash
curl -H "Content-Type: application/json" -d '{"id":"1", "jsonrpc":"2.0", "method": "state_getMetadata", "params":[]}' -o testing.json https://tfchain.dev.grid.tf/
```
