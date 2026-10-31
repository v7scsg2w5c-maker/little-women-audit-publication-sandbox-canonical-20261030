# Single clause letter closing: detailed changes

## current-winkle-single-clause-closing

Source: [chapter 10, line 164](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-10.xhtml#L164).

Occurrences: 1.

<code>&lt;/p&gt;&#10;						&lt;p epub:type="z3998:signature"&gt;&lt;abbr epub:type="z3998:given-name"&gt;N.&lt;/abbr&gt; Winkle&lt;/p&gt;</code> → <code>&lt;br/&gt;&#10;							&lt;span epub:type="z3998:signature"&gt;&lt;abbr epub:type="z3998:given-name"&gt;N.&lt;/abbr&gt; Winkle&lt;/span&gt;&lt;/p&gt;</code>.

[Exact patch](../../changes/current-winkle-single-clause-closing/baseline.patch).

Proposed commit:

```text
Update “N. Winkle” markup (chapter 10, line 164)
```
