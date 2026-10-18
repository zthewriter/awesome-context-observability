# Awesome Context Observability [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools that show how AI consumes, uses, and cites your docs and content when it generates responses.

Rendered list: https://zthewriter.github.io/awesome-context-observability/

Page views cannot tell you what happens when an AI answers from your content and the reader never opens the page. These tools can: they show which passages reached an AI answer, which AI answer engines cite your pages, which agents read your docs, and what an AI retrieved before it responded. To understand how content turns into passages and passages into answers, start with the learning resources at the end of this list.

This list is not about docs tools in general. Every entry links to the tool's own documentation for the feature that provides this visibility.

## Contents

- [Answer and passage analytics](#answer-and-passage-analytics)
- [Docs platforms with AI insights](#docs-platforms-with-ai-insights)
- [AI search visibility](#ai-search-visibility)
- [AI agent and crawler traffic](#ai-agent-and-crawler-traffic)
- [Retrieval tracing](#retrieval-tracing)
- [Standards and specs](#standards-and-specs)
- [Learning resources](#learning-resources)

## Answer and passage analytics

Tools that answer questions from your content and show, per question, what content was used.

- [Kapa.ai](https://docs.kapa.ai/analytics/) - Answer engine over your technical content, with analytics on the questions users ask and coverage gaps where documentation is missing.
- [MCP Studio](https://docs.appatools.com/mcp-studio/guides/action-predictive-analytics) - Builds MCP servers from your docs and other sources, and shows the exact passage behind each answer, content gaps, and how confidently each page was matched. Disclosure: maintained by the author of this repo.

## Docs platforms with AI insights

Documentation platforms whose analytics report on AI agents and assistants, not only human readers.

- [GitBook](https://gitbook.com/docs/analytics/insights/agents-and-mcp) - Site insights report the agents and crawlers reading your docs through Markdown, `llms.txt`, and MCP, and what visitors ask its AI assistant.
- [Mintlify](https://www.mintlify.com/docs/optimize/analytics) - Analytics separate human and agent traffic and include AI assistant conversations, topics, and search queries.

## AI search visibility

Tools that track how AI answer engines, such as ChatGPT, Perplexity, and Google AI Overviews, mention and cite your pages.

- [AirOps](https://docs.airops.com/insights/citations) - Tracks every URL cited in AI answers for the prompts you follow, with citation rate and share, and connects content updates to changes in citations.
- [OtterlyAI](https://help.otterly.ai) - Monitors brand mentions and cited URLs across AI search engines.
- [Peec AI](https://docs.peec.ai) - Measures how visible your brand is in AI responses, with share of voice, position, and sentiment.
- [Profound](https://docs.tryprofound.com) - Answer engine insights showing which engines cite your content, citation share by platform, topic, and prompt, and watched pages.

## AI agent and crawler traffic

Tools that show which AI agents and crawlers fetch your content, and let you control access.

- [Cloudflare AI Crawl Control](https://developers.cloudflare.com/ai-crawl-control/) - Monitor and control how AI services access your website content.
- [Known Agents](https://knownagents.com/docs) - Agent analytics that identify the AI agents and crawlers visiting your site.

## Retrieval tracing

Open source tools for teams running their own RAG or agent systems, which record what was retrieved and passed to the model on each request.

- [Arize Phoenix](https://arize.com/docs/phoenix) - Open source tracing and evaluation for LLM applications, including the documents retrieved for each request.
- [Langfuse](https://langfuse.com/docs) - Open source tracing for LLM and agent applications, including retrieval steps with their inputs and outputs.

## Standards and specs

The standards these tools measure against.

- [Agent-Friendly Documentation Spec](https://agentdocsspec.com/spec/) - Checks across seven categories for whether agents can discover, fetch, and read a docs site, with a reference checker, [afdocs](https://github.com/agent-ecosystem/afdocs).
- [llms.txt](https://llmstxt.org/) - Proposal for a Markdown file that lists a site's important pages for AI tools.
- [Model Context Protocol](https://modelcontextprotocol.io/) - Open standard for connecting AI agents to tools and content.

## Learning resources

- [Context for AI](https://github.com/zthewriter/context-for-ai) - How AI turns content into passages, answers, and decisions, with documentation templates and checklists. Disclosure: maintained by the author of this repo.
- [Measuring delivered context](https://github.com/zthewriter/harness-engineering-cookbook/blob/v1.0.0/recipes/12-observe-delivered-context.md) - Recipe that matches each channel delivering your docs to the kind of tool in this list that observes it. Disclosure: maintained by the author of this repo.

## Contributing

Contributions are made by pull request only, and every pull request is reviewed and approved by the maintainer before it is merged. Read the [contribution guidelines](https://github.com/zthewriter/awesome-context-observability/blob/main/CONTRIBUTING.md) for what qualifies, where to add a tool, and the entry format.
