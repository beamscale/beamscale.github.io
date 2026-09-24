# BeamScale marketing site

Astro marketing site for BeamScale Hosted Gleam.

## Stack

- Astro 7
- static output
- GitHub Pages
- zero client framework dependencies
- vanilla JavaScript only for the mobile navigation drawer

## Local development

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
```

The GitHub Pages workflow deploys `main` automatically.

## Design notes

The site intentionally avoids a conventional centered SaaS layout. Desktop uses a persistent runtime-map rail beside the content, while mobile converts that rail into a drawer. The header is sticky and the footer is a full editorial closing section.

Marketing claims and terminology are derived from the current `bmscl-cli`, `bmscl-compiler`, and `bmscl-supervisor` contracts: fresh tenant process per invocation, capability-scoped I/O, signed deterministic artifacts, generation pinning, and changed-only deployment by build digest.
