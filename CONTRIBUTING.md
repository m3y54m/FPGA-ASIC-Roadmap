# Contributing

Contributions are welcome. To keep the roadmap practical and trustworthy, please follow these guidelines.

## 1. Prioritize beginners

- Prefer resources that a newcomer to FPGA/ASIC design can follow.
- Advanced or specialized resources are welcome, but place them under the relevant advanced topic and do not mark them 👶.

## 2. Choose credible, current resources

- Prefer free and open resources. Paid resources should be added only when they clearly offer more than the free alternatives.
- Prefer primary and authoritative sources: official vendor documentation, standards bodies, university courses, well-known textbooks, and tool documentation.
- Do not add every publication from the same author or site; each entry needs a clear reason to be there.
- Make sure the resource is up to date and the link works.

## 3. Format

Resources are list items under the most relevant heading:

```markdown
- [📘👶💎 Title - Author](https://example.com)
```

- Type: 📘 book, 🎞️ video or course, 📝 article, blog post or documentation, 🔗 other (tool, website, repository).
- Quality (optional): 👶 beginner-friendly, 💎 well-known reference with comprehensive content.
- Put each resource under the most relevant topic of the Roadmap. Topics are ordered by learning sequence and tagged **Required**, **Recommended** or **Optional**; if you propose a new topic, suggest where it fits in the order and which priority it deserves.
- Do not add the same link twice within the same section.
- Run `npx markdownlint-cli --config .markdownlint.json README.md` before opening a pull request; CI runs the same check.
- A weekly "Link check" workflow (and every pull request touching Markdown) verifies that all links work. Sites that block bots can be excluded in `.github/lychee.toml`.
