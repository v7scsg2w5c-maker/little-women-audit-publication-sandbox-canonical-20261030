# Vivan language removal: detailed changes

## vivan

Source: [chapter 1, line 85](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-1.xhtml#L85).

Occurrences: 1.

<code>&lt;i xml:lang="es"&gt;vivan&lt;/i&gt;</code> → <code>&lt;i&gt;vivan&lt;/i&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/vivan/baseline.patch).

Proposed commit:

```text
Remove language markup from “vivan” (chapter 1, line 85)
```
