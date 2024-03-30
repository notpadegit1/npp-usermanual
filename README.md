Notepad++ User Manual
=======

[**Notepad++ User Manual**](https://npp-user-manual.org) is built collaboratively, and your contribution is very welcome. Before submitting a pull request (PR), please check our [contribution rules](CONTRIBUTION.md) to prevent your PR from being rejected.

Summary
=======

* [Getting started](content/docs/getting-started.md)
* [Working with Files](content/docs/files.md)
* [Editing](content/docs/editing.md)
* [Searching](content/docs/searching.md)
* [Views](content/docs/views.md)
* [Sessions, Workspaces, and Projects](content/docs/session.md)
* [Function List](content/docs/function-list.md)
* [Auto-Completion](content/docs/auto-completion.md)
* [Syntax Highlighting - Built-in Languages](content/docs/programing-languages.md)
* [Syntax Highlighting - User Defined Languages](content/docs/user-defined-language-system.md)
* [Macros - Task Automation](content/docs/macros.md)
* [Running External Commands](content/docs/run-menu.md)
* [Plugins](content/docs/plugins.md)
* [Plugin Communication](content/docs/plugin-communication.md)
* [Command Line Arguments](content/docs/command-prompt.md)
* [Preferences](content/docs/preferences.md)
* [Configuration Files Details](content/docs/config-files.md)
* [Themes](content/docs/themes.md)
* [Localization - User Interface Translation](content/docs/binary-translation.md)
* [User Interface](content/docs/user-interface.md)
* [Upgrading](content/docs/upgrading.md)
* [Right Click - Edit with Notepad++](content/docs/shell-extension.md)
* [Ghost Typing](content/docs/ghost-typing.md)
* [Other Resources](content/docs/other-resources.md)
* [User Manual History](content/docs/history.md)
* [Copyright & License](content/docs/license.md)


How to test site locally
=======

**Notepad++ User Manual** website is generated by [Hugo](https://gohugo.io/) by using [hugo-book theme](https://github.com/alex-shpak/hugo-book).
In order to visualize the site (with your modification) on your computer locally, you have to download [Hugo **extended** version](https://github.com/gohugoio/hugo/releases) firstly (v68.3 is currently recommended for compatibility purposes).
Go to the root of Notepad++ User Manual repository under your bash shell (use `Git bash` under windows) then type `HUGODIR\hugo.exe server --minify --theme book`

```txt
donh@MYPC MINGW64 /c/husbandIsNotATM/npp-usermanual (adapt_hugo_book_theme)
$ /c/tmp/hugo/hugo_ext/hugo.exe server --minify --theme book
Building sites …
                   | EN
+------------------+----+
  Pages            | 23
  Paginator pages  |  0
  Non-page files   |  0
  Static files     | 14
  Processed images |  0
  Aliases          |  0
  Sitemaps         |  1
  Cleaned          |  0

Total in 69 ms
Watching for changes in C:\husbandIsNotATM\npp-usermanual\{content,themes}
Watching for config changes in C:\husbandIsNotATM\npp-usermanual\config.toml
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disablastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop

```

Type [http://localhost:1313/](http://localhost:1313/) on the adress bar of your browser et voilà!
