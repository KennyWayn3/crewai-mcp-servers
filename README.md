# CrewAI MCP Servers & Skills

Production-ready MCP servers and CrewAI skills for AI agents. Built by AI, for AI.

## Products

| Product | Description | Price | PyPI | GitHub |
|---------|-------------|-------|------|--------|
| **Web Search MCP Server** | Search the web and extract content from URLs. Give your AI agent real-time web access. | $49 | `pip install crewai-web-search-mcp` | [Repo](https://github.com/KennyWayn3/web-search-mcp-server) |
| **Code Review Automation MCP** | Automated code review for AI agents. Analyze PRs, detect issues, suggest fixes. | $49 | `pip install code-review-automation` | [Repo](https://github.com/KennyWayn3/code-review-automation) |
| **Document Intelligence Server** | Intelligent document processing - extract, classify, summarize PDFs and images using vision LLMs. | $49 | `pip install document-intelligence-server` | [Repo](https://github.com/KennyWayn3/document-intelligence-server) |
| **Browser Automation Skills Pack** | Pre-built CrewAI skills for web automation: form filling, data extraction, multi-step navigation. | $49-$299 | `pip install crewai-browser-automation-skills-pack` | [Repo](https://github.com/KennyWayn3/crewai-browser-automation-skills-pack) |
| **Enterprise Integration Skills Pack** | CrewAI skills for REST APIs, web scraping, email parsing, document processing, and database connectors. | $49-$299 | `pip install crewai-enterprise-integration-skills-pack` | [Repo](https://github.com/KennyWayn3/crewai-enterprise-integration-skills-pack) |

## Quick Start

```bash
# Install any MCP server with uvx
uvx crewai-web-search-mcp
uvx code-review-automation

# Add to your Claude Desktop config:
# {"mcpServers": {"server-name": {"command": "uvx", "args": ["package-name"]}}}
```

## About

These products are created by an autonomous AI business crew that researches, builds, and publishes AI agent tooling.
Each product is published to PyPI, GitHub, HuggingFace, and Gumroad.

## License
MIT