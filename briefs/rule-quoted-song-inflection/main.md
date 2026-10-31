# Quoted song inflection

Identify the Crinkle lullaby, both serenade fragments and the hummed Kennst du das land excerpt as z3998:song. Their surrounding narration explicitly describes singing or humming. Add the one-line span for Crinkle; the serenade’s line structure comes from the linked prerequisite, so the composed result contains one wrapper and both song labels. These are required semantic corrections under the quoted-song rule.

| Location | Current → proposed | Exact patch |
| --- | --- | --- |
| [chapter 1, line 111](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-1.xhtml#L111) | <code>&lt;blockquote&gt;</code> → <code>&lt;blockquote epub:type="z3998:song"&gt;</code> | [Patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/crinkle-song-markup/baseline.patch) |
| [chapter 33, line 32](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-33.xhtml#L32) | <code>&lt;blockquote&gt;</code> → <code>&lt;blockquote epub:type="z3998:song"&gt;</code> | [Patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-003/baseline.patch) |
| [chapter 12, line 202](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-12.xhtml#L202) | <code>&lt;blockquote&gt;&#10;				&lt;p&gt;“Alone, alone, ah! woe, alone,”&lt;/p&gt;&#10;			&lt;/blockquote&gt;&#10;			&lt;p class="continued"&gt;and at the lines⁠—&lt;/p&gt;&#10;			&lt;blockquote epub:type="z3998:verse"&gt;</code> → <code>&lt;blockquote epub:type="z3998:song"&gt;&#10;				&lt;p&gt;“Alone, alone, ah! woe, alone,”&lt;/p&gt;&#10;			&lt;/blockquote&gt;&#10;			&lt;p class="continued"&gt;and at the lines⁠—&lt;/p&gt;&#10;			&lt;blockquote epub:type="z3998:song"&gt;</code> | [Patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/ir51-serenade-semantics/baseline.patch) |

[Complete changes and proposed messages](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/audit-evidence/account-copy-v1/briefs/rule-quoted-song-inflection/appendix.md).

![Standard Ebooks digital text — Ebook context render — chapter 1 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0068.png)

[Standard Ebooks digital text — Ebook context render — chapter 1 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0069.png).

![Standard Ebooks digital text — Ebook context render — chapter 33 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0130.png)

[Standard Ebooks digital text — Ebook context render — chapter 33 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0131.png).
