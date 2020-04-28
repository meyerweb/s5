# Simple Standards-based Slide Show System (S5)

A simple slideshow system originally conceived and written in 2005 as a way to recreate Opera’s Presentation Mode display in any browser, using JavaScript to fill in the features Opera had natively at the time, while allowing Opera to present S5 files without needing the JS.  So far as the author is aware, Presentation Mode no longer exists in Opera.  S5 was also designed to be compatible with [the XOXO microformat](http://microformats.org/wiki/xoxo), which does still exist.

The [original project](https://meyerweb.com/eric/tools/s5/) was eventually given a Public Domain license.  This copy of S5 uses the closest GitHub equivalent, the Unlicense.  To see a basic slideshow in action, load `s5-intro.html` into a browser.  For a mostly-blank slideshow file, see `s5-blank.html`.  Documentation, both of plain S5 and XOXO-compatible S5, can be found in the `docs` directory.

This copy is made public as a historical reference, **not** as an active project.  Thus, Issues and Pull Requests for this repository will not be enabled or accepted.  Forks of this repository for personal use, enhancement, and development are permitted (encouraged, even).

Note that S5, as it exists here, is good mostly for text-heavy bullet-point slides.  Images can be added, but will require extra styling to manage.  There are no transition effects, either between slides or of content within a slide; such effects were too computationally expensive in 2005, and the CSS necessary to make most of them work hadn’t been invented yet.  Much better browser-based slideshow systems have been invented in the 15 years between S5 and when this repository went public, and should be investigated if you’re looking for a robust browser-based slideshow solution.  Again, this is a historical document more than anything else.

Somewhere along the way, S5 picked up [a Wikipedia entry](https://en.wikipedia.org/wiki/S5_(file_format)), a fact which remains entirely baffling.

—Eric Meyer
 28 April 2020
