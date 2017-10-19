jabbrev-revtex-bug
==================

What is this repo for?
----------------------

"Minimal" exemple to illustrate https://github.com/compholio/jabbrv/issues/2

I just took the [revtex](https://journals.aps.org/revtex) sample, and tried to adapt it's bibtex style to use [jabbrv](http://www.compholio.com/latex/jabbrv/).
It' obviously a failure.
Now the question is why?


How to see the bug?
-------------------
Just uncomment `%\bibliographystyle{apsrev4-1-jabbrv.bst}` and comment the line above.
I suppose revtex4-1 to be system-wide installed.
