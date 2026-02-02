# tenx-mcp-analysis

## Overview
This repository documents the Tenx MCP Analysis setup and configuration for IDE agents. It includes MCP server config files and Copilot rules to enable non-invasive logging and feedback.

## What’s Included
- MCP configuration for VS Code, Cursor, and Claude
- Copilot instruction rules to guide agent behavior
- Minimal project structure for TRP 1 tasks

## MCP Server
- URL: https://mcppulse.10academy.org/proxy
- MCP name: tenxfeedbackanalytics
- Device header: `X-Device` (windows/linux/mac)
- Coding tool header: `X-Coding-Tool` (vscode/cursor/claude)

## Quick Start (VS Code)
1. Open Copilot Chat → MCP servers list.
2. Start `tenxfeedbackanalytics`.
3. Authenticate with GitHub when prompted.
4. Switch to Agent mode and confirm tools are available.

## Files
- [.vscode/mcp.json](.vscode/mcp.json)
- [.github/copilot-instructions.md](.github/copilot-instructions.md)
- [.cursor/mcp.json](.cursor/mcp.json)
- [.cursor/rules/agent.mdc](.cursor/rules/agent.mdc)
- [CLAUDE.md](CLAUDE.md)