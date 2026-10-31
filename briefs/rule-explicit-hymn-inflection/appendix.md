# Explicit hymn inflection: detailed changes

## git-09-current-proposal-002

Source: [local.css, line 52](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/css/local.css#L52).

Occurrences: 5.

<code>[epub&#124;type~="z3998:poem"]</code> → <code>[epub&#124;type~="z3998:hymn"] p,&#10;[epub&#124;type~="z3998:poem"]</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-002/baseline.patch).

Proposed commit:

```text
Change “[epub|type~="z3998:poem"]” to “[epub|type~="z3998:hymn"] p, [epub|type~="z3998:poem"]” (local.css, line 52)
```

## git07-current-ch43-explicit-hymn-carrier

Source: [chapter 43, line 131](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-43.xhtml#L131).

Occurrences: 1.

<code>&lt;blockquote epub:type="z3998:song"&gt;</code> → <code>&lt;blockquote epub:type="z3998:song z3998:hymn"&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git07-current-ch43-explicit-hymn-carrier/baseline.patch).

Proposed commit:

```text
Explicit hymn inflection (chapter 43, line 131)
```
