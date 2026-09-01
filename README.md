# Catenda Help Center

> Documentation for Catenda — the open BIM collaboration platform for the construction industry.

The complete Catenda Help Center as plain Markdown — the same articles you can read on
the help center, in a form that AI assistants, chatbots and search tools can
consume directly.

**Just want to read the documentation?** Go to <https://support.catenda.com>. That is the
version to search, share and link to. This repository is the machine-readable
twin of it.

## Point an AI assistant here

Give your assistant this URL and it can find everything else:

```
https://raw.githubusercontent.com/catenda/help-center/main/llms.txt
```

`llms.txt` is a small standard index (see <https://llmstxt.org>) listing every
article with a one-line summary and a link to its Markdown source.
`llms-full.txt` is the whole help center concatenated into one file, for tools
that would rather have a single document than follow links.

## What is in here

| Path | Contents |
| --- | --- |
| `llms.txt` | Index of every English article — the entry point |
| `llms-full.txt` | Every English article inlined in one file |
| `<lang>/llms.txt` | The same index for one language |
| `markdown/<lang>/articles/` | One Markdown file per article |
| `images/` | Screenshots and diagrams the articles refer to |

Article paths mirror the help center's own URLs, so you can go from one to the
other by hand: the article at `https://support.catenda.com/en/articles/8064548-models-as-documents`
is at `markdown/en/articles/8064548-models-as-documents.md`.

## Languages

| Language | Index | Articles |
| --- | --- | --- |
| English | `en/llms.txt` | `markdown/en/articles/` |
| Dutch — Nederlands | `nl/llms.txt` | `markdown/nl/articles/` |
| Norwegian Bokmål — Norsk bokmål | `nb/llms.txt` | `markdown/nb/articles/` |
| German — Deutsch | `de/llms.txt` | `markdown/de/articles/` |
| French — Français | `fr/llms.txt` | `markdown/fr/articles/` |
| Japanese — 日本語 | `ja/llms.txt` | `markdown/ja/articles/` |

English is the original. The other languages are machine-translated, and every
translated article says so in a note at the top.

## Updates

This repository is regenerated automatically whenever the help center changes,
so it tracks the published documentation rather than lagging behind it. Nothing
here is edited by hand.

## Found a mistake?

Because every file is generated, an issue or pull request opened here cannot
reach the documentation — the next rebuild would overwrite it. Report it through
<https://support.catenda.com> instead and the correction will appear in both the help
center and this mirror.
