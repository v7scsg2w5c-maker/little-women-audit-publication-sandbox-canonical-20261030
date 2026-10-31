# Single clause letter closing

In chapter 10, “Yours respectably, N. Winkle” forms one valediction/signature clause. Put it in one paragraph, with a br before the signature and a z3998:signature span around N. Winkle. This implements the single-clause closing rule (required; high confidence). The composed Winkle persona span nests inside the signature span; the closing repair does not establish the performer’s identity.

| Location | Current → proposed | Exact patch |
| --- | --- | --- |
| [chapter 10, line 164](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-10.xhtml#L164) | <code>&lt;/p&gt;&#10;						&lt;p epub:type="z3998:signature"&gt;&lt;abbr epub:type="z3998:given-name"&gt;N.&lt;/abbr&gt; Winkle&lt;/p&gt;</code> → <code>&lt;br/&gt;&#10;							&lt;span epub:type="z3998:signature"&gt;&lt;abbr epub:type="z3998:given-name"&gt;N.&lt;/abbr&gt; Winkle&lt;/span&gt;&lt;/p&gt;</code> | [Patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/current-winkle-single-clause-closing/baseline.patch) |

[Complete changes and proposed messages](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/audit-evidence/account-copy-v1/briefs/rule-single-clause-letter-closing/appendix.md).

![Standard Ebooks digital text — Ebook context render — chapter 10 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0074.png)

[Standard Ebooks digital text — Ebook context render — chapter 10 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0075.png).
