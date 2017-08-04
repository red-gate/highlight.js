# Highlight.js - fork with T-SQL highlighting

This is a fork of the [highlight.js](https://github.com/isagalaev/highlight.js) by [isagalaev](https://github.com/isagalaev), that contains only a ready-to-use T-SQL syntax highlighting.

## Sample usage
We used this library for [readyroll vsts extension](https://github.com/red-gate/readyroll-vsts-extension).
In [this PR](https://github.com/red-gate/readyroll-vsts-extension/pull/16) we added highlighting using the original highlight.js library from CDN. It didn't contain the support for T-SQL, so we forked the original repo into this one and added T-SQL highlighting ourselves. We then created a [npm package](https://www.npmjs.com/package/highlight.js-tsql) and used it in [this PR](https://github.com/red-gate/readyroll-vsts-extension/pull/20).

## License

Highlight.js is released under the BSD License. See [LICENSE][7] file
for details.

## Links

The official site for the library is at <https://highlightjs.org/>.

Further in-depth documentation for the API and other topics is at
<http://highlightjs.readthedocs.io/>.

Authors and contributors are listed in the [AUTHORS.en.txt][8] file.

[1]: http://highlightjs.readthedocs.io/en/latest/api.html#inithighlightingonload
[2]: http://highlightjs.readthedocs.io/en/latest/css-classes-reference.html
[3]: http://highlightjs.readthedocs.io/en/latest/api.html#highlightblock-block
[4]: http://highlightjs.readthedocs.io/en/latest/api.html#configure-options
[5]: https://highlightjs.org/download/
[6]: http://highlightjs.readthedocs.io/en/latest/building-testing.html
[7]: https://github.com/isagalaev/highlight.js/blob/master/LICENSE
[8]: https://github.com/isagalaev/highlight.js/blob/master/AUTHORS.en.txt
