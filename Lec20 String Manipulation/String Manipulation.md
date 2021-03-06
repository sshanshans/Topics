String Manipulation
========================================================
author: Albert Y. Kim
date: Monday April 18, 2016






Strings
========================================================

In computer science a **(character) string** is any finite sequence of characters (i.e.,
letters, numerals, symbols and punctuation marks).

In R they are denoted with double quotation marks.



stringr Package
========================================================

Like handling dates, handling text is a non-glamorous but necessary task.  The
`stringr` package tries to alleviate this problem.

`stringr` simplifies string operations by eliminating options that you don’t need 95% of 
the time. i.e. not the most powerful, but tradeoff is gain in simplicity. 

If ever you need to do very advanced string manipulations, languages like Python
and Ruby are better suited for the task.



Auto-Complete
========================================================

`stringr` uses consistent function names and arguments i.e. almost all functions
in the `stringr` package start with `str_`.

So if you forget a function, type `str_` in the console and press TAB to get a
list of auto-completions.




stringr Package
========================================================

* `stringr` provides pattern matching functions to `str`
    + `_detect`
    + `_locate`
    + `_extract`
    + `_match`
    + `_replace`
    + `_split`
* Note that many of these funcitions also have an `_all` version. See
`str_replace()` and `str_replace_all`


