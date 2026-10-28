# IDEA StatiCa MCP

**AI assistants that work with IDEA StatiCa — steel connections, concrete sections and IDEA Open Model files.**

IDEA StatiCa MCP is a free [Model Context Protocol](https://modelcontextprotocol.io) (MCP) server. Claude, Cursor, VS Code Copilot,
Windsurf, Gemini, Codex and other AI assistants use it to work with IDEA StatiCa through IDEA StatiCa's own Connection and RCS REST
services on your PC, and with IDEA Open Model (IOM) files without IDEA StatiCa. One self-contained program: no plug-in, no .NET to install.

**Download:** [the latest release](https://github.com/SHMH-MCPs/ideastatica-mcp-releases/releases/latest) — run `Install-IDEA-StatiCa-MCP.cmd` from it. Requires IDEA StatiCa 26.0 or 26.1 (not Basic) for the Connection and RCS tools.

## What it does (0.1.0 verified live on IDEA StatiCa 26.1.0.5973; 26.0 and typed manufacturing operations not yet verified)
- **Connection projects:** open, create, import from IOM, save and close; connections, members, load effects, parameters, materials, sections, bolt assemblies
- **Design:** templates and the Connection Library; manufacturing operations (bolt grids, welds, plates, cuts, stiffeners) directly in IDEA StatiCa 26.1
- **Calculation and results:** calculate as background jobs; IDEA StatiCa's verdict per connection and check; detailed results
- **Deliverables:** calculation reports (PDF, Word, HTML), IOM, IFC and DWG exports, project summaries, revision comparison
- **RCS:** reinforced concrete sections — sections, internal forces, materials, calculation and results
- **IOM files:** read, check, compare and write, without IDEA StatiCa
- **Any other operation** of IDEA StatiCa's published Connection and RCS APIs, through a typed, risk-classified generic call
- **24 workflow skills,** served as MCP prompts

Destructive changes need your confirmation after a preview; every change is read back; backups are made before high-impact operations;
project content stays on your PC; a read-only mode is available. Results are IDEA StatiCa's output for the engineer's review.

## Supported versions
| IDEA StatiCa | Status |
|---|---|
| 26.1 (Connection Rest API 5.0) | designed for, **not yet tested** |
| 26.0 (Connection Rest API 4.0) | designed for (fewer tools), **not yet tested** |

The live tools need a licensed IDEA StatiCa (the Basic licence type has no API). It cannot drive Checkbot or the desktop applications.

IDEA StatiCa MCP is a product of the SHMH-MCPs family (Revit, Navisworks, 3ds Max, ETABS, SAFE, STAAD MCP). IDEA StatiCa is a trademark
of IDEA StatiCa s.r.o.; IDEA StatiCa MCP is not affiliated with or endorsed by IDEA StatiCa.
