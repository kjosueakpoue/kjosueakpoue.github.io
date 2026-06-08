# Akpoué Kouamé Josué — Academic Website

Personal academic website of Akpoué Kouamé Josué, linguist specializing in formal semantics of Ivorian and Kwa languages, and developer of linguistic computational tools.

**Live site:** [kjosueakpoue.github.io](https://kjosueakpoue.github.io)

## Structure

```
website/
├── _config.yml          Jekyll configuration
├── _data/               YAML data files (publications, talks, news, tools, fieldwork)
├── _includes/           Reusable HTML components (nav, footer, entries)
├── _layouts/            Page templates
├── assets/
│   ├── css/             Stylesheets
│   ├── fonts/           Self-hosted fonts (if any)
│   └── img/             Images
├── en/                  English version
│   ├── index.html       Homepage EN
│   └── pages/           Inner pages EN
├── fr/                  French version
│   ├── index.html       Homepage FR
│   └── pages/           Inner pages FR
└── resources/
    └── pdf/
        ├── articles/    Published articles (PDF)
        ├── handouts/    Conference handouts
        ├── slides/      Presentation slides
        └── cv/          CV (PDF)
```

## Adding content

All content is managed via YAML files in `_data/`. To add a new entry:
- **Publication** → edit `_data/publications.yml`
- **Talk** → edit `_data/talks.yml`
- **News** → edit `_data/news.yml`
- **Tool release** → edit `_data/releases.yml`
- **Fieldwork session or tool** → edit `_data/fieldwork.yml`

## License

Site code: MIT  
Content (texts, data): [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
