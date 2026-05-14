![logo](./whisper-logo.png)

# Whisper Security

**Real-time infrastructure intelligence for security teams. See the internet in God Mode.**

Whisper unifies the internet's infrastructure data - routing, DNS, hosting, and
ownership - into a single knowledge graph, so security teams can see every
connection behind any domain, IP, or network and understand how it changed in
real time.

## WhisperGraph

WhisperGraph is a custom graph engine built from first principles for internet
infrastructure intelligence: **7.38B nodes and 38.98B edges** across 20 entity
types, with unlimited traversal depth.

- **DNS** - 12B+ resolution edges
- **BGP & routing** - 116K ASNs, 2.5M prefixes, continuous streaming
- **GeoIP** - 54K cities, 424 countries
- **WHOIS** - organization, registrar, and email records
- **Threat intelligence** - 40 live feeds
- **Web links** - 10.9B hyperlinks
- **DNSSEC** and historical state tracking - time-travel queries over how
  infrastructure changed

Search any domain, IP, or network and pivot from one indicator to every shared
piece of infrastructure - who owns it, what it hosts, how it routes - in a
single multi-hop [Cypher](https://www.whisper.security/glossary/cypher) query,
in milliseconds.

### What makes it different

- **Zero-GC architecture** - no garbage-collection pauses, predictable
  millisecond-scale latency at billion-node scale
- **Native data types** - IPv4, IPv6, CIDR, and ASN are first-class types in
  the engine, not strings, so range and containment queries are instant
- **Real-time ingestion** - continuous BGP and DNS streaming, not daily
  snapshots
- **Explainable scoring** - every risk score ships with the complete chain of
  evidence, grounded in information theory rather than black-box ML

## Open source

| Repository | Description |
|------------|-------------|
| [whisper-graph-mcp](https://github.com/whisper-sec/whisper-graph-mcp) | Open-source, self-hostable [MCP](https://www.whisper.security/docs/mcp/setup) server for WhisperGraph - query the internet's infrastructure & threat-intel graph (DNS, BGP, GeoIP, WHOIS) via Cypher. TypeScript, Apache-2.0. |
| [whisper-skills](https://github.com/whisper-sec/whisper-skills) | Agent Skills for the WhisperGraph MCP server - threat investigation, Cypher query authoring, and brand-protection sweeps. |
| [STIX](https://github.com/whisper-sec/STIX) | STIX 2.1 support for standardized threat-intelligence sharing across security platforms and tools. |

## Integrate

WhisperGraph is available through three access patterns:

- **REST + Cypher API** - direct programmatic access to the graph
- **Native connectors** - Splunk, Microsoft Sentinel, OpenCTI, and Cortex XSOAR
- **MCP** - connect AI agents (Claude, Cursor, VS Code, Windsurf) to the graph;
  start with [whisper-graph-mcp](https://github.com/whisper-sec/whisper-graph-mcp)

Get a free API key at [console.whisper.security](https://console.whisper.security/sign-up).

## About us

Whisper was founded in January 2025 out of Antler's fall 2024 program - selected
from the top 0.4% of more than 8,000 startups - by **Kaveh Ranjbar**
(Co-Founder & CEO, 25-year internet-infrastructure veteran and former RIPE NCC
CIO) and **Soroush Rafiee Rad** (Co-Founder & CPSO, mathematician with dual PhDs
in mathematical logic and the philosophy of science). The company raised €1.6M
in pre-seed capital from Antler, Atlas Ventures, Volve Capital, D11z Ventures,
and Tioga Trust, and is advised by former ICANN Chairman Maarten Botterman and
APNIC Chief Scientist Geoff Huston.

We believe that understanding the internet's infrastructure is the key to
defending it.

## Resources

- **Website** - [whisper.security](https://www.whisper.security)
- **Product** - [whisper.security/product](https://www.whisper.security/product)
- **Documentation** - [whisper.security/docs](https://www.whisper.security/docs)
- **MCP setup** - [whisper.security/docs/mcp/setup](https://www.whisper.security/docs/mcp/setup)
- **Console** - [console.whisper.security](https://console.whisper.security)
- **Contact** - [whisper.security/contact-us](https://www.whisper.security/contact-us)
- **Support** - support@whisper.security

## Security

If you discover a security vulnerability in any of our repositories, please
email security@whisper.security. We take security seriously and will respond
promptly to all reports.

## License

Licensing is specified per repository - see each repository's `LICENSE` file.
