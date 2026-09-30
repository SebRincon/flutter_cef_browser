# flutter_cef_browser

A Flutter macOS (Apple silicon) plugin that embeds the Chromium Embedded Framework
(CEF) as native browser views, with tabs, navigation, JavaScript evaluation,
screenshots, downloads, DevTools-protocol input and multi-process helper apps.

It is developed for [Jet Browser](https://github.com/SebRincon/jet-browser), which
pins this repository by commit SHA as a git submodule. See [PROVENANCE.md](PROVENANCE.md).

## CEF assets

CEF binaries are not in this repository. Before a macOS build, place a matching CEF
distribution in `macos/Frameworks/` (ignored by git):

- `Chromium Embedded Framework.framework` (versioned bundle)
- `include/` (the headers of that same CEF build)
- `libcef_dll_wrapper.a`
- `LICENSE.txt` and `CREDITS.html`

Jet's `scripts/install_cef.sh` installs and hash-verifies the build it uses (CEF
147.0.11 / Chromium 147.0.7727.138). Never pair a framework with headers from another
CEF version.

## License

BSD 3-Clause, see [LICENSE](LICENSE). CEF and Chromium are covered by the notices in
[licenses/](licenses/).
