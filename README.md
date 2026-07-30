# JSON-LD Schema Builder

This tool builds valid JSON-LD structured data for a local business, organization, software application, or article. You pick a type, fill the fields, and it outputs a ready-to-paste script block that labels your page's content for search and AI systems.

**Live demo:** https://0xelitesystem.github.io/json-ld-schema-builder/

## What it does

Choose one of four types: LocalBusiness, Organization, SoftwareApplication, or Article. Fill the fields the type needs, such as name, description, address, author, or offer. The tool assembles a correct JSON-LD object inside an application/ld+json script tag and updates it live, with a copy button.

Blank fields are omitted. The structured data should describe what is genuinely on the page; validate the output with a structured-data testing tool before relying on it. This pairs with the FAQ schema and citability references in the wider collection.

## Aesthetic

A library card catalog: manila index cards, a typewriter heading, tabbed type selection, and a dark output card.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. Copyright (c) 2026 0xelitesystem.
