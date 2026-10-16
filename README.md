# Catalyst SD-WAN Manager API — Field Guide

A working reference for the Cisco Catalyst SD-WAN (Software-Defined Wide Area Network) Manager API, Release 26.1 with 20.18 deltas: what each endpoint family does, where the data comes from, how to implement it, and how to stay inside the rate limits.

**Read it:** https://alexpacket.github.io/sdwan-manager-api-guide/

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The guide: one self-contained HTML page |
| `404.html` | Shown by GitHub Pages for missing paths |
| `favicon.svg`, `favicon.png` | Site icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Updating the guide

1. Edit `index.html` (or replace it with a new export).
2. Commit with a message that says what changed, for example `26.1.1: interface export interval`.
3. Push to `main`. GitHub Pages republishes in about a minute.

Tag a commit when a new Cisco release changes the API (for example `release-26.1`) so earlier versions stay easy to find.

## Contributing

Corrections are welcome as pull requests (PRs). Cite the Cisco document and release that supports the change.

## Disclaimer

Built from public Cisco documentation (Cisco DevNet API guides and Cisco configuration guides). Not an official Cisco publication. Verify endpoint names and limits against your own Manager's `/apidocs` before production use.
