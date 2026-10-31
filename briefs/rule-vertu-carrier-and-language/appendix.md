# Vertu carrier and language: detailed changes

## vertu

Source: [chapter 33, line 105](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-33.xhtml#L105).

Occurrences: 1.

<code>&lt;i xml:lang="la"&gt;vertu&lt;/i&gt;; so it was rather a failure after all. Poor as he is, he didn’t forget a servant or a child in the house; and not a soul here, from the French laundrywoman to Miss Norton, forgot him. I was so glad of that.&lt;/p&gt;</code> → <code>vertu; so it was rather a failure after all. Poor as he is, he didn’t forget a servant or a child in the house; and not a soul here, from the French laundrywoman to Miss Norton, forgot him. I was so glad of that.&lt;/p&gt;</code>.

[Exact patch](https://github.com/v7scsg2w5c-maker/little-women-audit-publication-sandbox-canonical-20261030/blob/c97210078bab885768f4f915fa218a8712f58b3d/changes/vertu/baseline.patch).

Proposed commit:

```text
Remove language markup from “vertu; so it was rather a failure after all. Poor as he is, he didn’t forget a servant or a child in the house; and not a soul here, from the French laundrywoman to Miss Norton, forgot him. I was so glad of that.” (chapter 33, line 105)
```
