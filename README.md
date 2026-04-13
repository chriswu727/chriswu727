# Hi, I'm Yichen

AI Product Engineer building tools that turn LLMs into real, useful products.

UIUC (BS) + Northwestern (MS) in Computer Engineering.

## What I'm Building

### [Argus](https://github.com/chriswu727/argus) — AI-Powered QA Testing Agent

Give it a URL, it explores your web app like a real user and finds bugs that scripted tests miss.

- 18 MCP tools for Claude Code / Cursor integration
- Auto-verification: every action (delete, edit, toggle) is automatically checked for persistence
- 16 detection types: dead links, broken images, SEO, accessibility, performance, logic bugs
- Tested on 9+ real websites with zero false positives
- `pip install argus-testing` | [PyPI](https://pypi.org/project/argus-testing/)

### [Sibyl](https://github.com/chriswu727/sibyl) — AI Deep Research Agent

Ask any question — Sibyl searches across multiple sources, cross-references findings, and generates executive-quality reports with analysis and predictions.

- 11 MCP tools: `research`, `compare`, `swot`, `trends`, `timeline`, `fetch_market_data`, `chart`
- 4 search engines in parallel: DuckDuckGo, Google News, Reddit, Wikipedia (all free, no API keys)
- Deep research pipeline: sub-question decomposition, iterative gap-filling, cross-source sentiment analysis, section-by-section synthesis
- Financial data + chart generation embedded in PDF reports
- Multi-LLM: DeepSeek, OpenAI, Gemini, GLM, Anthropic (auto-detect)
- `pip install sibyl-research`

## Tech

Python | Playwright | LiteLLM | MCP | FastAPI | Docker | Kubernetes | AWS

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/yichen-wu-198951234)
