The Nabi Grid System
================

An adaptive grid without media queries. Not suitable for production.
---

This grid system is an attempt at an adaptive grid without using any media queries. This box, the main content, is 30em wide. The three sidebars are each 10em wide. Everything is floated to the left.

When the screen size changes, or when the text size is increased by the user, the columns collapse in on one another. the third column will slide under the second one, then they will both slide under the first sidebar. Eventually, this one long sidebar will get suted underneath the main content area. When the viewport gets smaller than 30em, this main contect box will shrink accordingly.

It was a neat little proof-of-concept, but it's nowhere near a viable alternative to media queries. <strong>Each column must be longer than the one to its right for this to work</strong>, which limits the kinds of designs that you can do.
