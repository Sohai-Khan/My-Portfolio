## GitHub Copilot Chat

- Extension Version: 0.28.5 (prod)
- VS Code: vscode/1.101.2
- OS: Windows

## Network

User Settings:
```json
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: timed out after 10 seconds
- DNS ipv6 Lookup: Error (8 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (1 ms)
- Electron fetch (configured): timed out after 10 seconds
- Node.js https: timed out after 10 seconds
- Node.js fetch: timed out after 10 seconds
- Helix fetch: timed out after 10 seconds

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.112.21 (156 ms)
- DNS ipv6 Lookup: timed out after 10 seconds
- Proxy URL: None (1 ms)
- Electron fetch (configured): timed out after 10 seconds
- Node.js https: HTTP 200 (7787 ms)
- Node.js fetch: timed out after 10 seconds
- Helix fetch: timed out after 10 seconds
