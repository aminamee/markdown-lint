---
title: MD005 - Inconsistent indentation for list items at the same level
tags:  [bullet, ul, indentation]
alias: list-indent
---

This rule is triggered when list items are parsed as being at the same level,
but don't have the same indentation:

    * Item 1
        * Nested Item 1
        * Nested Item 2
       * A misaligned item

Usually this rule will be triggered because of a typo. Correct the indentation
for the list to fix it:

    * Item 1
      * Nested Item 1
      * Nested Item 2
      * Nested Item 3

