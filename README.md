# RDP (rdp)
The Remote Desktop Protocol (RDP) is a proprietary network protocol developed by Microsoft that provides a graphical interface to connect to another computer over a network. RDP transmits keyboard, mouse, display, and audio data between client and host, enabling remote administration, virtual desktops, and remote work scenarios. The protocol typically operates on TCP and UDP port 3389 and is defined in the MS-RDPBCGR open specification.

This index also covers the Refinitiv Data Platform (RDP) from LSEG — a cloud REST API platform for financial market data, historical pricing, ESG scores, and analytics.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/rdp/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Financial Data, LSEG, Microsoft, Networking, RDP, Remote Access, Remote Desktop, Refinitiv

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [RDP Connection Schema](json-schema/rdp-connection.json) | Schema for an RDP connection profile (.rdp file equivalent) |
| [RDP Session Schema](json-schema/rdp-session-schema.json) | Schema for an active or historical RDP session on an RDS host |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [RDP Connection Structure](json-structure/rdp-connection-structure.json) | Field-level documentation for the connection profile object |

## JSON-LD Context

| Context | Description |
|---------|-------------|
| [RDP Context](json-ld/rdp-context.jsonld) | JSON-LD context mapping RDP concepts to linked data identifiers |

## Examples

| Example | Description |
|---------|-------------|
| [RDP Connection Example](examples/rdp-connection-example.json) | Example connection profile for a corporate development server |
| [RDP Session Example](examples/rdp-session-example.json) | Example active session record from an RDS host |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [RDP Vocabulary](vocabulary/rdp-vocabulary.yml) | Domain vocabulary for RDP protocol concepts and Refinitiv Data Platform terms |

## Specifications & References

- [MS-RDPBCGR (Microsoft Open Specification)](https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-rdpbcgr/)
- [MS-RDSOD Remote Desktop Services Overview](https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-rdsod/)
- [Microsoft Remote Desktop Services Docs](https://learn.microsoft.com/en-us/windows-server/remote/remote-desktop-services/welcome-to-rds)
- [LSEG Refinitiv Data Platform APIs](https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis)

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
