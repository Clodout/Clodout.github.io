# Clodout website

Public product, privacy, and support pages for Clodout.

The site is dependency-free static HTML and is deployed to GitHub Pages. The
canonical privacy policy is maintained at `privacy/index.html`.

This repository is platform-neutral. Android-specific implementation,
architecture, build, release, and changelog documentation belongs in
`clodout-android`; future iOS-specific documentation belongs in its iOS
repository. Shared user guides can be added under `/docs/` here when they become
substantial, with platform subsections only where user workflows differ.

## Local preview

Serve the repository root with any static HTTP server, then open the displayed
local URL. For example:

```powershell
npx serve .
```

## Public pages

- Home: <https://clodout.github.io/>
- Privacy: <https://clodout.github.io/privacy/>
- Support: <https://clodout.github.io/support/>

The planned custom domain is `clodout.haseeb.ca`.
