# quoted song line structure

Wrap each quoted song line in a span inside its stanza paragraph: the chapter 12 serenade refrain and the chapter 33 hummed German line. The stanza rule requires one span per line and no trailing br after the last or only line. Keep the existing words, quotation marks and German language markup. These are required structural corrections (high confidence); their song-block semantics are supplied by the composed package.

| Location | Current → proposed | Exact patch |
| --- | --- | --- |
| [chapter 12, line 203](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-12.xhtml#L203) | <code>&lt;p&gt;“Alone, alone, ah! woe, alone,”&lt;/p&gt;</code> → <code>&lt;p&gt;&#10;					&lt;span&gt;“Alone, alone, ah! woe, alone,”&lt;/span&gt;&#10;				&lt;/p&gt;</code> | [Patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/serenade-line-stanza/baseline.patch) |
| [chapter 33, line 33](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-33.xhtml#L33) | <code>&lt;p&gt;‘&lt;i xml:lang="de"&gt;Kennst du das land&lt;/i&gt;,’&lt;/p&gt;</code> → <code>&lt;p&gt;&#10;						&lt;span&gt;‘&lt;i xml:lang="de"&gt;Kennst du das land&lt;/i&gt;,’&lt;/span&gt;&#10;					&lt;/p&gt;</code> | [Patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/kennst-line-stanza/baseline.patch) |

[Complete changes and proposed messages](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/audit-evidence/account-copy-v1/briefs/rule-quoted-song-line-structure/appendix.md).

![Standard Ebooks digital text — Ebook context render — chapter 12 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0001.png)

[Standard Ebooks digital text — Ebook context render — chapter 12 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0002.png).

![Standard Ebooks digital text — Ebook context render — chapter 33 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0218.png)

[Standard Ebooks digital text — Ebook context render — chapter 33 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0219.png).

