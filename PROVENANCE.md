# Provenance

This package is the `flutter_cef_browser` plugin used by
[Jet Browser](https://github.com/SebRincon/jet-browser).

- Source: `flutter_cef_browser/` in `SebRincon/webview_cef` (a private repository) at commit
  `a14b590260a0ed334a7a089db0f733f5818bc0c9`.
- Changes for Jet (2026-09): an acknowledged, in-process Chromium input dispatcher for
  native-view browser automation, limited to a fixed allowlist of mouse, key and
  insert-text methods. Changed files: `lib/src/cef_browser_controller.dart`,
  `macos/Classes/Bridge/CEFBridge.h`, `macos/Classes/Bridge/CEFBridge.mm`,
  `macos/Classes/FlutterCefBrowserPlugin.mm`.
- Publishing metadata: the pubspec and podspec homepages point at this repository and
  the podspec author matches the license holder (they were placeholders).
- `licenses/` holds the CEF license and the Chromium credits (xz-compressed) of the CEF
  147 build this plugin was verified with.

Git history in this repository pins the exact content; the previous per-file checksum
manifest was dropped because the commit SHA now serves that purpose.
