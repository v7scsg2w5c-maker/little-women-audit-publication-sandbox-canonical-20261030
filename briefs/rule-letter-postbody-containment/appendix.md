# Letter postbody containment: detailed changes

## git-09-current-proposal-005

Source: [chapter 15, line 35](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-15.xhtml#L35).

Occurrences: 1.

<code>&lt;p epub:type="z3998:signature"&gt;“&lt;abbr epub:type="z3998:given-name"&gt;S.&lt;/abbr&gt; Hale,&lt;/p&gt;&#10;				&lt;p epub:type="z3998:signature"&gt;“Blank Hospital, Washington”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“&lt;abbr epub:type="z3998:given-name"&gt;S.&lt;/abbr&gt; Hale,&lt;/p&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Blank Hospital, Washington”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-005/baseline.patch).

Proposed commit:

```text
Update ““S. Hale, “Blank Hospital, Washington”” markup (chapter 15, line 35)
```

## git-09-current-proposal-006

Source: [chapter 16, line 46](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-16.xhtml#L46).

Occurrences: 1.

<code>&lt;p epub:type="z3998:signature"&gt;“Meg.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Meg.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-006/baseline.patch).

Proposed commit:

```text
Update ““Meg.”” markup (chapter 16, line 46)
```

## git-09-current-proposal-007

Source: [chapter 16, line 53](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-16.xhtml#L53).

Occurrences: 1.

<code>&lt;p epub:type="z3998:signature"&gt;“Topsy-Turvy Jo.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Topsy-Turvy Jo.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-007/baseline.patch).

Proposed commit:

```text
Update ““Topsy-Turvy Jo.”” markup (chapter 16, line 53)
```

## git-09-current-proposal-008

Source: [chapter 16, line 116](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-16.xhtml#L116).

Occurrences: 1.

<code>&lt;p epub:type="z3998:signature"&gt;“Little Beth.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Little Beth.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-008/baseline.patch).

Proposed commit:

```text
Update ““Little Beth.”” markup (chapter 16, line 116)
```

## git-09-current-proposal-009

Source: [chapter 16, line 121](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-16.xhtml#L121).

Occurrences: 1.

<code>&lt;p epub:type="z3998:valediction"&gt;“Your affectionate daughter,&lt;/p&gt;&#10;				&lt;p epub:type="z3998:signature"&gt;“Amy Curtis March.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:valediction"&gt;“Your affectionate daughter,&lt;/p&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Amy Curtis March.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-009/baseline.patch).

Proposed commit:

```text
Update ““Your affectionate daughter, “Amy Curtis March.”” markup (chapter 16, line 121)
```

## git-09-current-proposal-010

Source: [chapter 16, line 127](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-16.xhtml#L127).

Occurrences: 1.

<code>&lt;p epub:type="z3998:valediction"&gt;“Yours Respectful,&lt;/p&gt;&#10;				&lt;p epub:type="z3998:signature"&gt;“Hannah Mullet.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:valediction"&gt;“Yours Respectful,&lt;/p&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Hannah Mullet.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-010/baseline.patch).

Proposed commit:

```text
Update ““Yours Respectful, “Hannah Mullet.”” markup (chapter 16, line 127)
```

## git-09-current-proposal-011

Source: [chapter 16, line 133](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-16.xhtml#L133).

Occurrences: 1.

<code>&lt;p epub:type="z3998:signature"&gt;“Colonel Teddy.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Colonel Teddy.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-011/baseline.patch).

Proposed commit:

```text
Update ““Colonel Teddy.”” markup (chapter 16, line 133)
```

## git-09-current-proposal-012

Source: [chapter 16, line 138](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-16.xhtml#L138).

Occurrences: 1.

<code>&lt;p epub:type="z3998:valediction"&gt;“Your sincere friend and servant,&lt;/p&gt;&#10;				&lt;p epub:type="z3998:signature"&gt;“James Laurence.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:valediction"&gt;“Your sincere friend and servant,&lt;/p&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“James Laurence.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-012/baseline.patch).

Proposed commit:

```text
Update ““Your sincere friend and servant, “James Laurence.”” markup (chapter 16, line 138)
```

## current-mother-signature-footer

Source: [chapter 12, line 28](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-12.xhtml#L28).

Occurrences: 1.

<code>&lt;p epub:type="z3998:signature"&gt;“Mother.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;“Mother.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/current-mother-signature-footer/baseline.patch).

Proposed commit:

```text
Update ““Mother.”” markup (chapter 12, line 28)
```

## git-09-current-proposal-013

Source: [chapter 21, line 30](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-21.xhtml#L30).

Occurrences: 1.

<code>&lt;p epub:type="z3998:valediction"&gt;“Your devoted &lt;span epub:type="z3998:signature"&gt;John&lt;/span&gt;.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:valediction"&gt;“Your devoted &lt;span epub:type="z3998:signature"&gt;John&lt;/span&gt;.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-013/baseline.patch).

Proposed commit:

```text
Update ““Your devoted John.”” markup (chapter 21, line 30)
```

## git-09-current-proposal-016

Source: [chapter 31, line 50](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-31.xhtml#L50).

Occurrences: 1.

<code>&lt;p epub:type="z3998:signature"&gt;Amy.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:signature"&gt;Amy.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-016/baseline.patch).

Proposed commit:

```text
Update “Amy.”” markup (chapter 31, line 50)
```

## git-09-current-proposal-020

Source: [chapter 31, line 64](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-31.xhtml#L64).

Occurrences: 1.

<code>&lt;p&gt;“Adieu; I embrace you tenderly. &lt;i epub:type="z3998:signature" xml:lang="fr"&gt;Votre Amie.&lt;/i&gt;”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p&gt;“Adieu; I embrace you tenderly. &lt;i epub:type="z3998:signature" xml:lang="fr"&gt;Votre Amie.&lt;/i&gt;”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-020/baseline.patch).

Proposed commit:

```text
Update ““Adieu; I embrace you tenderly. Votre Amie.”” markup (chapter 31, line 64)
```

## git-09-current-proposal-024

Source: [chapter 31, line 80](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-31.xhtml#L80).

Occurrences: 1.

<code>&lt;p&gt;“Ever your &lt;span epub:type="z3998:signature"&gt;Amy&lt;/span&gt;.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p&gt;“Ever your &lt;span epub:type="z3998:signature"&gt;Amy&lt;/span&gt;.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-024/baseline.patch).

Proposed commit:

```text
Update ““Ever your Amy.”” markup (chapter 31, line 80)
```

## git-09-current-proposal-029

Source: [chapter 33, line 77](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-33.xhtml#L77).

Occurrences: 1.

See exact patch.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-029/baseline.patch).

Proposed commit:

```text
Letter postbody containment (chapter 33, line 77)
```

## git-09-current-proposal-033

Source: [chapter 39, line 160](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-39.xhtml#L160).

Occurrences: 1.

<code>&lt;p epub:type="z3998:valediction"&gt;“Yours gratefully, &lt;span epub:type="z3998:signature"&gt;Telemachus&lt;/span&gt;.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:valediction"&gt;“Yours gratefully, &lt;span epub:type="z3998:signature"&gt;Telemachus&lt;/span&gt;.”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/git-09-current-proposal-033/baseline.patch).

Proposed commit:

```text
Update ““Yours gratefully, Telemachus.”” markup (chapter 39, line 160)
```

![Standard Ebooks digital text — Ebook context render — chapter 16 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0134.png)

[Standard Ebooks digital text — Ebook context render — chapter 16 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0135.png).

![Standard Ebooks digital text — Ebook context render — chapter 16 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0136.png)

[Standard Ebooks digital text — Ebook context render — chapter 16 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0137.png).

![Standard Ebooks digital text — Ebook context render — chapter 16 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0138.png)

[Standard Ebooks digital text — Ebook context render — chapter 16 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0139.png).

![Standard Ebooks digital text — Ebook context render — chapter 16 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0140.png)

[Standard Ebooks digital text — Ebook context render — chapter 16 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0141.png).

![Standard Ebooks digital text — Ebook context render — chapter 16 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0142.png)

[Standard Ebooks digital text — Ebook context render — chapter 16 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0143.png).

![Standard Ebooks digital text — Ebook context render — chapter 16 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0144.png)

[Standard Ebooks digital text — Ebook context render — chapter 16 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0145.png).

![Standard Ebooks digital text — Ebook context render — chapter 12 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0072.png)

[Standard Ebooks digital text — Ebook context render — chapter 12 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0073.png).

![Standard Ebooks digital text — Ebook context render — chapter 21 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0146.png)

[Standard Ebooks digital text — Ebook context render — chapter 21 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0147.png).

![Standard Ebooks digital text — Ebook context render — chapter 31 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0150.png)

[Standard Ebooks digital text — Ebook context render — chapter 31 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0151.png).

![Standard Ebooks digital text — Ebook context render — chapter 31 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0156.png)

[Standard Ebooks digital text — Ebook context render — chapter 31 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0157.png).

![Standard Ebooks digital text — Ebook context render — chapter 31 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0162.png)

[Standard Ebooks digital text — Ebook context render — chapter 31 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0163.png).

![Standard Ebooks digital text — Ebook context render — chapter 33 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0172.png)

[Standard Ebooks digital text — Ebook context render — chapter 33 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0173.png).

![Standard Ebooks digital text — Ebook context render — chapter 39 — crop](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0178.png)

[Standard Ebooks digital text — Ebook context render — chapter 39 — full context render](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/raw/c97210078bab885768f4f915fa218a8712f58b3d/assets/image-0179.png).
