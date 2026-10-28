# Calvin Rutherford — portfolio

A single-page personal portfolio using HTML, CSS and vanilla JavaScript. The
existing dark cyan design, animated background and responsive cards are kept in
`index.html`; no build step or JavaScript framework is required.

## Preview locally

Requires Python 3 (or another static HTTP server):

```sh
python3 -m http.server 8080 --bind 127.0.0.1
# Open http://localhost:8080
```

`SWE_Resume.pdf` is the locally linked resume. Fonts load from Google Fonts when
available, with system-font fallbacks. Social and contact links are maintained
in the HTML; project descriptions and links live in the inline `projects` array.

## Featured projects

- **Magistrate:** engineering-assistant prototype, documented architecture and
  test evidence. Personal execution and live/device acceptance remain blocked.
- **GiniCast:** phase-one acquisition, standardization and audit pipeline.
  Forecasting and dashboards are roadmap items.
- **Sunset Sheriff:** Godot town-defense game in the `police-simulator` repository,
  with local build instructions and native tests. No hosted playable demo is
  represented by a placeholder link.

Before publishing, check the page at phone and desktop widths, follow project
and resume links, review current repository status, and confirm career/contact
information with the owner. Local preview and HTML/link checks do not establish
that a public site or email address is live. This change does not deploy the site.
