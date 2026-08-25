<p align="center">
  <img src="./assets/solidrpc-cover.jpg" alt="SolidRPC — reliable RPC infrastructure for blockchain builders" width="100%">
</p>

<p align="center">
  <a href="https://solidrpc.io"><strong>Website</strong></a>
  ·
  <a href="https://solidrpc.io/docs"><strong>Documentation</strong></a>
  ·
  <a href="https://solidrpc.io/docs/networks"><strong>Networks</strong></a>
  ·
  <a href="https://dashboard.solidrpc.io/register"><strong>Start free</strong></a>
</p>

## Replace your multi-provider RPC stack with one managed RPC layer

To keep RPC reliable, production teams often connect several providers, then build and operate their own routing, health checks, retries, fallback logic, monitoring, and incident response on top.

When a provider fails and that customer-owned reliability layer fails with it, an infrastructure problem becomes a customer-facing production incident.

**SolidRPC moves that work behind one integration.** Your team integrates SolidRPC. We operate the nodes and upstream capacity, route supported requests to qualified infrastructure, shift traffic when it degrades, monitor the fleet, and drive recovery.

### What your team stops owning

| Without SolidRPC | With SolidRPC |
|---|---|
| Several RPC provider integrations | One SolidRPC integration |
| Homegrown routing, retries, and fallback | Health- and method-aware managed routing |
| Monitoring every provider and node | Continuous fleet and upstream monitoring |
| Manual failover orchestration | Requests routed to qualified healthy capacity |
| RPC incidents on your team's pager | AI-assisted diagnosis and bounded recovery |
| Full and archive node operations | Operated infrastructure for supported request paths |

### Routing protects the request first. Operations repair the infrastructure behind it.

When an upstream becomes unhealthy or falls behind, SolidRPC can remove it from rotation and route requests to qualified failover capacity. Monitoring and AI-assisted operations then diagnose, repair, and verify the affected infrastructure. Risky actions remain human-approved and audited.

## One endpoint format across supported EVM networks

```text
https://rpc.solidrpc.io/YOUR_API_KEY/evm/{chainId}
```

Use the same JSON-RPC integration pattern for full and archive access, historical state, logs, and network-dependent `debug_*` and `trace_*` methods. Check exact coverage in the live [network and method catalog](https://solidrpc.io/docs/networks).

Start with the [getting started guide](https://solidrpc.io/docs/getting-started), try the [keyless public RPC endpoints](https://solidrpc.io/docs/public-rpc), or review [security](https://solidrpc.io/security).

---

<p align="center">
  <strong>One RPC integration. Reliability operations included.</strong><br>
  <a href="https://dashboard.solidrpc.io/register">Create an account</a>
  ·
  <a href="https://solidrpc.io/contact">Talk to an engineer</a>
</p>
