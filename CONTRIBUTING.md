# Contributing to Official MCP Servers

A curated list of official MCP servers. We organize links to servers hosted in their own repositories or documented by their vendors.

## Adding a Server

### Entry Format

Add your server to the end of the relevant category in `README.md`:

```markdown
- **[Name](https://github.com/org/repo)** - Short description of what it does
```

If the server has no public repository, link to the vendor's official MCP documentation instead. You can add the Claude connector page at the end of the line when one exists:

```markdown
- **[Name](https://vendor.com/docs/mcp)** - Short description ([Claude](https://claude.com/marketplace/connectors/name))
```

### Where to Add

- Add to the end of the matching category in `README.md`.
- If no existing category fits, open an issue to propose a new one.

### Requirements

- Official server backed by the product or company it connects to, or a widely used open source project
- Public repository or official vendor documentation with working setup instructions
- Actively maintained (archived and abandoned projects are not accepted)
- Description must be short, 10 words or fewer. No lengthy paragraphs.
- Real community usage. Brand new projects that were just created are not accepted. Give your server time to mature and gain users before submitting.

### PR Title

`Add server: name`

## Important

- This repository curates links only. Each server lives in its own repo or vendor docs.
- Verify your links work before submitting.
- We review all submissions and may decline servers that do not meet the quality bar.

## Help

- Check existing issues and PRs first
- Open a new issue for questions
- Visit the server's own repo or docs for server-specific help
