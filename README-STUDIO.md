# Holy Spirit Studios fork

Upstream: [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp)

## Studio changes

- **whatsapp-mcp-server**: `WHATSAPP_API_BASE_URL`, `WHATSAPP_STORE_DB` for shared agent-server hosting
- **whatsapp-bridge**: `WHATSAPP_HTTP_PORT` (default 8080)

Installed via `holy-skills-whatsapp` (`holy whatsapp setup`). Agent fleet uses one bridge on `holy-agent-server` (`holy-whatsapp-mcp` service); agent proxies connect via `sharedBridgeUrl`.
