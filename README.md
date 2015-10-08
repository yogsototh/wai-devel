### wai-devel
[WAI] compliant development server for haskell web frameworks.

### Installation
- cd wai-devel
- stack build
- stack install

The wai-devel binary will now be in your ~/.local/bin you can use it freely.


### Usage
See the [wiki].

### Issues
Doesn't autorecompile due to changes in Template Haskell files due to a bug .


### Coming next

- Provide a dashboard page with compilation status, GC stats, and other such useful meta-information.
- Port to windows. This depends on ide-backend getting ported to Windows.
- Proper support for cabal binary users and their sandboxes.

[WAI]: http://www.yesodweb.com/book/web-application-interface
[wiki]: https://github.com/urbanslug/wai-devel/wiki
