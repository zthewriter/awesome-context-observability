# Contribution guidelines

Thank you for suggesting a tool. Please read this whole page first; most pull
requests that are not accepted missed one of the rules below.

## How contributions work

1. **Pull requests only.** Nobody pushes to `main` directly, including collaborators.
   `main` is protected.
2. **Every pull request is reviewed and approved by the maintainer,
   [@zthewriter](https://github.com/zthewriter), before it is merged.** The
   [CODEOWNERS](.github/CODEOWNERS) file makes that review required.
3. **The maintainer merges.** Contributors do not merge their own pull requests.
4. **Automated checks must pass**: the list format check and the link check.

You will get a first response within two business days. If a pull request is not
accepted, you will get a reason.

## What qualifies

A tool belongs on this list if it **shows, measures, or controls how AI systems
consume, use, or cite content** when they generate responses. For example, it shows:

- the passages or documents behind an AI answer,
- which pages AI answer engines cite, and how often,
- which AI agents and crawlers read your content, or
- what was retrieved and passed to a model on each request.

A tool does **not** qualify if it only:

- hosts or generates documentation, with no AI usage insights,
- measures human page views and engagement,
- checks writing style, spelling, or links, or
- monitors AI systems with no visibility into the content they used.

In addition, every tool must:

- **Be available now.** No waitlist-only products.
- **Have public documentation** for the observability feature. The link goes to that
  documentation, not a marketing page or pricing page.
- **Be maintained**, with documentation or releases updated in the last 12 months.

## Where to add your tool

Choose the one section that matches the tool's main observability feature:

| Section | For tools that |
|---|---|
| Answer and passage analytics | Answer from your content and show the content behind each answer |
| Docs platforms with AI insights | Host docs and report on AI agent or assistant usage |
| AI search visibility | Track mentions and citations in AI answer engines |
| AI agent and crawler traffic | Show or control AI agents and crawlers fetching content |
| Retrieval tracing | Record what a RAG or agent system retrieved per request |
| Standards and specs | Define what these tools measure (specs, not products) |
| Learning resources | Teach how AI uses content |

Add your entry in **alphabetical order** within that section. If no section fits,
open the pull request anyway and explain why in the description; a new section needs
at least two qualifying tools.

## Entry format

```markdown
- [Tool name](https://link-to-the-docs-for-the-feature) - Description.
```

- Use the tool's official name.
- Link to the documentation page for the observability feature.
- Write one sentence, under 30 words, starting with a capital letter and ending with a
  period.
- Describe what the tool shows, in plain words. No "best", "leading", "#1",
  "revolutionary", or other marketing language.
- Use American English and no em dashes.

## Affiliation

If you work for, own, or are paid by the tool you are adding, say so in the pull
request description. Affiliated submissions are welcome and are held to the same
rules. The maintainer's own project is marked in the list.

## Pull request checklist

- [ ] One tool per pull request
- [ ] The tool qualifies under "What qualifies"
- [ ] The link goes to documentation for the observability feature
- [ ] The entry is in the right section, in alphabetical order
- [ ] The description follows the entry format
- [ ] Any affiliation is disclosed in the pull request description

## Updating or removing an entry

Open a pull request with the change and the reason. Entries are removed when a tool
is discontinued, its documentation link stops working and has no replacement, or it
no longer qualifies.

## Code of conduct

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
