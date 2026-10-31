# Letter closing compound restructuring: detailed changes

## current-laurie-closing-footer-and-single-clause

Source: [chapter 12, line 36](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-12.xhtml#L36).

Occurrences: 1.

<code>&lt;p epub:type="z3998:valediction"&gt;“In a tearing hurry,&lt;/p&gt;&#10;				&lt;p epub:type="z3998:valediction"&gt;“Yours ever,&lt;/p&gt;&#10;				&lt;p epub:type="z3998:signature"&gt;“Laurie.”&lt;/p&gt;</code> → <code>&lt;footer role="presentation"&gt;&#10;					&lt;p epub:type="z3998:valediction"&gt;“In a tearing hurry,&lt;br/&gt;&#10;					Yours ever,&lt;br/&gt;&#10;					&lt;span epub:type="z3998:signature"&gt;Laurie.&lt;/span&gt;”&lt;/p&gt;&#10;				&lt;/footer&gt;</code>.

[Exact patch](../../changes/current-laurie-closing-footer-and-single-clause/baseline.patch).

Proposed commit:

```text
Change “In a tearing hurry, “Yours ever, “Laurie” to “In a tearing hurry, Yours ever, Laurie” (chapter 12, line 36)
```
