# AI Core docs

The documentation of [AI Core](https://github.com/aifivem/ai-core), the AI-ready FiveM framework, published at **[aifivem.com/docs](https://aifivem.com/docs)**.

## Writing

- One page per file: `page.mdx` is English, `page.tr.mdx` is its Turkish version. A page missing in a language falls back to English.
- Sidebar order lives in `meta.json`.
- Frontmatter: `title`, `description`, and an optional `icon` (a [Lucide](https://lucide.dev/icons) icon name).
- Available components: `Cards` / `Card`, `Callout`, `Steps` / `Step`, plus regular Markdown and tables.
- Link to other pages with absolute paths: `/docs/installation`, `/tr/docs/installation`.

Every page has an "Edit on GitHub" link. Open a pull request; once it is merged into `main`, the site rebuilds and the change goes live.
