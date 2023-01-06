# Fider

[Fider](https://fider.io) is a feedback portal that helps you build better products. Give your customers a voice and let them tell you what they need. Spend less time guessing and more time building the right product.

## Access

|                 |                                                      |
| --------------- | ---------------------------------------------------- |
| **URL**         | [https://fider.tainton.uk](https://fider.tainton.uk) |
| **Hosted On**   | [netcup VPS](/homelab/servers/vps)                   |
| **Monitored**   | :material-close:                                     |
| **SSO Enabled** | :material-check:                                     |


## User Traffic Flow

``` mermaid
graph LR
  A[User] --> B[Cloudflare];
  B --> C[Reverse Proxy];
  C --> D[Docker Container];
```
