# Default connection model selection: review screenshots

Visual evidence for apache/maka#5865. Captured in Chromium with the production React components, theme and styles, using a synthetic connection and a stubbed bridge. No real endpoint, secret or user configuration is included.

- before.png: original ProvidersPanel from upstream commit 064997019, with the reported no-enabled-model failure returned by the bridge.
- after.png: updated panel, explicitly selecting Model Beta for atomic enable-and-set-default.
- empty.png: updated panel with no known models, offering discovery or manual entry.

Prepared with Codex on behalf of liuxiaocs7. These files are PR review evidence and are not part of the implementation branch.
