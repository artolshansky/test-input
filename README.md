# TestInput

Having a text input bound with ngModel and a pattern validation, if you hold a letter key while focusing the input to enter a long string such as "aaaaaaaaaaaaa", after ~30 characters the browser freezes and does not respond anymore.

**The regexp is inefficient - o(n^2)**