---
chapter :     performance
section:      0
title:        Variable Definition
attribution:  jQuery Fundamentals
tags:         performance
---

Variables can be defined in one statement instead of several.

    // old & busted
    var test = 1;
    var test2 = function() { ... };
    var test3 = test2(test);

    // new hotness
    var test = 1,
        test2 = function() { ... },
        test3 = test2(test);

In self-executing functions, variable definition can be skipped all together.

    (function(foo, bar) { ... })(1, 2);
