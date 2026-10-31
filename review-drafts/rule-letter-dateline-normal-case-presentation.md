# Normal-case letter datelines

Keep letter datelines in normal case by adding font-variant: normal to the existing se:letter.dateline selector; retain right alignment. Header wrapping otherwise makes four chapter 33 datelines inherit small capitals. The Manual requires small capitals for separate-line salutations, not for these datelines, so this is a discretionary presentation choice (medium confidence). The combined letter comparison found the intended footer changes and no remaining unintended dateline changes.

| Location | Current → proposed | Exact patch |
| --- | --- | --- |
| [local.css](https://github.com/standardebooks/louisa-may-alcott_little-women/blob/38695106591f6060142dd1ad4da1d2aeded8ab8f/src/epub/css/local.css) | <code>text-align:</code> → <code>font-variant: normal;&#10;	text-align:</code> | [Patch](../changes/letter-dateline-normal-case-presentation/baseline.patch) |

[Complete changes and proposed messages](../briefs/rule-letter-dateline-normal-case-presentation/appendix.md).

