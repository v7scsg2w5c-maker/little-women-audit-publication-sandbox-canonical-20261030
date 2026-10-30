# Quoted song line structure: detailed changes

## serenade-line-stanza

Source: [chapter 12, line 203](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-12.xhtml#L203).

Occurrences: 1.

<code>&lt;p&gt;“Alone, alone, ah! woe, alone,”&lt;/p&gt;</code> → <code>&lt;p&gt;&#10;					&lt;span&gt;“Alone, alone, ah! woe, alone,”&lt;/span&gt;&#10;				&lt;/p&gt;</code>.

[Exact patch](../../changes/serenade-line-stanza/baseline.patch).

Proposed commit:

```text
Update ““Alone, alone, ah! woe, alone,”” markup (chapter 12, line 203)
```

## kennst-line-stanza

Source: [chapter 33, line 33](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/text/chapter-33.xhtml#L33).

Occurrences: 1.

<code>&lt;p&gt;‘&lt;i xml:lang="de"&gt;Kennst du das land&lt;/i&gt;,’&lt;/p&gt;</code> → <code>&lt;p&gt;&#10;						&lt;span&gt;‘&lt;i xml:lang="de"&gt;Kennst du das land&lt;/i&gt;,’&lt;/span&gt;&#10;					&lt;/p&gt;</code>.

[Exact patch](../../changes/kennst-line-stanza/baseline.patch).

Proposed commit:

```text
Update “‘Kennst du das land,’” markup (chapter 33, line 33)
```
