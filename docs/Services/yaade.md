# Yaade

[Yaade](https://github.com/EsperoTech/yaade) is an open-source, self-hosted, collaborative API development environment.

## Access

|                 |                                                                                         |
| --------------- | --------------------------------------------------------------------------------------- |
| **URL**         | [https://yaade.tainton.uk](https://yaade.tainton.uk)                                    |
| **Hosted On**   | Synology NAS                                                                            |
| **Monitored**   | :material-close:                                                                        |
| **SSO Enabled** | :material-close: ([EsperoTech/yaade#42](https://github.com/EsperoTech/yaade/issues/42)) |


## User Traffic Flow

``` mermaid
graph LR
  A[User] --> B[Cloudflare];
  B --> C[Reverse Proxy];
  C --> D[Docker Container];
```
