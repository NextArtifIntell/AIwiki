# Sublime

## Introduction

## Installation

- Download Sublime Text from [Homepage](https://www.sublimetext.com).
- Download Sublime Merge from [Homepage](https://www.sublimemerge.com/).
- Add `Licence`.

## Settings

- [Sublime](https://www.sublimetext.com/) and [Install Package Control](https://packagecontrol.io/installation)
- Install [Node.js](http://nodejs.org/): `brew install node` (**Compulsory**)

## Plugins

Add a series of useful plugins.

### Main Plugins

- [A File Icon](https://github.com/SublimeText/AFileIcon)
- [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter)
- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter)
    - CSS
        - [SublimeLinter-stylelint](https://github.com/SublimeLinter/SublimeLinter-stylelint)
            - A mighty CSS linter that helps you avoid errors and enforce conventions.
            - Install [Node.js](http://nodejs.org/): `brew install node` (**Compulsory**)
            - [stylelint](https://github.com/stylelint/stylelint): `npm install postcss stylelint`
        - [sublime-autoprefixer](https://github.com/sindresorhus/sublime-autoprefixer): [x]
    - HTML
        - [SublimeLinter-html-tidy](https://github.com/SublimeLinter/SublimeLinter-html-tidy)
            - [tidy-html5](https://github.com/htacg/tidy-html5): `brew install tidy-html5`
    - Java
        - [SublimeLinter-javac](https://github.com/SublimeLinter/SublimeLinter-javac)
            - [openjdk](https://openjdk.org/): `brew install openjdk@11`
    - JavaScript
        - [SublimeLinter-jshint](https://github.com/SublimeLinter/SublimeLinter-jshint)
            - JSHint is a program that flags suspicious usage in programs written in JavaScript.
            - Install [Node.js](http://nodejs.org/): `brew install node` (**Compulsory**)
            - [jshint](https://github.com/jshint/jshint): `npm install jshint`
        - [SublimeLinter-eslint](https://github.com/SublimeLinter/SublimeLinter-eslint)
            - ESLint is a tool for identifying and reporting on patterns found in JavaScript code.
            - Install [Node.js](http://nodejs.org/): `brew install node` (**Compulsory**)
            - [eslint](https://github.com/eslint/eslint): `npm install eslint`
    - JSON
        - [SublimeLinter-json](https://github.com/SublimeLinter/SublimeLinter-json)
            - Interface to the [JSON parser](http://docs.python.org/3/library/json.html?highlight=json.loads#json.loads) built into Sublime Text.
    - LaTeX
        - [SublimeLinter-chktex](https://github.com/SublimeLinter/SublimeLinter-chktex)
            - [TexLive](https://www.tug.org/texlive/): `brew install mactex`
    - Lua
        - [SublimeLinter-lua](https://github.com/SublimeLinter/SublimeLinter-lua)
            - [Lua](https://www.lua.org/): `brew install Lua`
        - [SublimeLinter-luacheck](https://github.com/SublimeLinter/SublimeLinter-luacheck)
            - [luarocks](https://luarocks.org/): `brew install luarocks`
            - [luarocks](https://luarocks.org/): `luarocks install luacheck`
    - Markdown
        - [SublimeLinter-contrib-markdownlint](https://github.com/jonlabelle/SublimeLinter-contrib-markdownlint)
            - Install [Node.js](http://nodejs.org/): `brew install node` (**Compulsory**)
            - [Markdownlint-cli](https://github.com/igorshubovych/markdownlint-cli): `npm install markdownlint-cli`
                - [markdownlint](https://github.com/DavidAnson/markdownlint)
    - Python
        - [SublimeLinter-flake8](https://github.com/SublimeLinter/SublimeLinter-flake8)
            - [flake8](https://github.com/PyCQA/flake8): `pip3 install flake8`
        - [SublimeLinter-pycodestyle](https://github.com/SublimeLinter/SublimeLinter-pycodestyle)
            - [pycodestyle](https://github.com/PyCQA/pycodestyle): `pip3 install pycodestyle`
        - [SublimeLinter-pydocstyle](https://github.com/SublimeLinter/SublimeLinter-pydocstyle)
            - [pydocstyle](https://github.com/PyCQA/pydocstyle): `pip3 install pydocstyle`
        - [SublimeLinter-mypy](https://github.com/SublimeLinter/SublimeLinter-mypy)
            - [mypy](https://github.com/python/mypy): `pip3 install mypy`
        - [live-py-plugin](https://github.com/donkirkby/live-py-plugin): [x]
    - Shell
        - [SublimeLinter-shellcheck](https://github.com/SublimeLinter/SublimeLinter-shellcheck)
            - [shellcheck](https://github.com/koalaman/shellcheck): `brew install shellcheck`
- [LSP](https://github.com/sublimelsp)
    - Install [Node.js](http://nodejs.org/): `brew install node` (**Compulsory**)
        - The [Node.js](https://nodejs.org/) is required by this server and make sure that it's at least a version 14.
    - [LSP for Sublime](https://lsp.sublimetext.io/)
    - JSON: [LSP-json](https://github.com/sublimelsp/LSP-json)
    - LaTeX: [LSP-TexLab](https://github.com/sublimelsp/LSP-TexLab)
    - Lua: [LSP-Lua](https://github.com/sublimelsp/LSP-lua)
    - Python
        - [LSP-pyright](https://github.com/sublimelsp/LSP-pyright)
        - [LSP-ruff](https://github.com/sublimelsp/LSP-ruff)
            - [ruff](https://github.com/astral-sh/ruff):`pip3 install ruff`
        - [LSP-file-watcher-chokidar](https://github.com/sublimelsp/LSP-file-watcher-chokidar)
    - YAML: [LSP-yaml](https://github.com/sublimelsp/LSP-yaml)
    - Markdown: [LSP-marksman](https://github.com/sublimelsp/LSP-marksman): [x]
- [Origami](https://github.com/SublimeText/Origami)
- [TrailingSpaces](https://github.com/SublimeText/TrailingSpaces)
- [GitSavvy](https://github.com/timbrel/GitSavvy)
- [AutomaticPackageReloader](https://github.com/randy3k/AutomaticPackageReloader): [x]
- [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements): [x]
- [Sublime_rainbow_csv](https://github.com/mechatroner/sublime_rainbow_csv): [x]
- [Sublime-text-git](https://github.com/kemayo/sublime-text-git): [x]
- [gitignore](https://github.com/github/gitignore): [x] - (**deprecated**)
- [RainbowBrackets](https://github.com/absop/RainbowBrackets): [x] - (**deprecated**)
- [TabsExtra](https://facelessuser.github.io/TabsExtra/installation/): [x] - (**deprecated**)
- [PackageResourceViewer](https://github.com/skuroda/PackageResourceViewer): [x] - (**deprecated**)

### For Markdown

- [Markdown Editing](https://github.com/SublimeText-Markdown/MarkdownEditing)
    - MultiMarkdown: `View -> Syntax -> Open all with current extension as... -> Markdown -> MultiMarkdown`
    - [Github flavoured Markdown](https://github.github.com/gfm)
    - [MultiMarkdown](https://fletcherpenney.net/multimarkdown)
- [Markdown Preview](https://github.com/facelessuser/MarkdownPreview)
    - Insert `[{"keys": ["alt+m"], "command": "markdown_preview", "args": { "target": "browser", "parser": "markdown"}}]`  in `Key Bindings`.
    - [python-markdown-extension](https://python-markdown.github.io/extensions/), [python-markdown-usage-nodes](https://facelessuser.github.io/pymdown-extensions/usage_notes/), and [Third-Party-Extensions](https://github.com/Python-Markdown/markdown/wiki/Third-Party-Extensions)
        - [MathJax](https://www.mathjax.org/): [MathJax Support](https://facelessuser.github.io/MarkdownPreview/extras/)
        - [KaTex](https://katex.org/): [KaTex Support](https://facelessuser.github.io/MarkdownPreview/extras/#katex-support)
    - Parser
        - You can use the builtin [Python Markdown](https://github.com/Python-Markdown/markdown) parser (offline) or use the [GitHub Markdown API](https://developer.github.com/v3/markdown/) or [GitLab Markdown API](https://docs.gitlab.com/ee/api/markdown.html) (online) for the conversion.
        - Markdown preview using the [python-markdown](https://github.com/Python-Markdown/markdown) with syntax highlighting via [Pygments](https://github.com/pygments/pygments) and optional 3rd party extensions ([pymdown-extensions](http://facelessuser.github.io/pymdown-extensions/usage_notes/)).
        - pygments
            - [packagecontrol-pygments](https://github.com/packagecontrol/pygments)
            - [pygments](https://github.com/pygments/pygments)
        - python-markdown
            - [sublime-markdown](https://github.com/facelessuser/sublime-markdown)
            - [markdown](https://github.com/Python-Markdown/markdown)
        - pymdownx
            - [sublime-pymdownx](https://github.com/facelessuser/sublime-pymdownx)
            - [pymdown-extensions](https://github.com/facelessuser/pymdown-extensions)
- [LiveReload](https://github.com/alepez/LiveReload-sublimetext3)
    - Add `{"enabled_plugins": ["SimpleReloadPluginDelay", "SimpleRefresh"]}` in `LiveReload -> Settings - User`.
- [Markdown Table Editor](https://github.com/vkocubinsky/SublimeTableEditor)
    - Add `"enable_table_editor": true,` in `Packages/User/MultiMarkdown.sublime-settings`.
- [MarkdownTOC](https://github.com/naokazuterada/MarkdownTOC): [x]

### For Latex

- [skim](https://skim-app.sourceforge.io/):
    - `Check for file changes` and `Reload automatically`
    - `Preferences -> Sync -> X Check for file changes` and `Preset: Sublime Text preset`
- [macTex](https://tug.org/mactex/)
- [LSP-TexLab](https://github.com/sublimelsp/LSP-TexLab)
- [SublimeLinter-chktex](https://github.com/SublimeLinter/SublimeLinter-chktex)
- latexcs
- [LaTexTools](https://latextools.readthedocs.io/en/latest/): [x]
- [LaTeXing](https://github.com/LaTeXing/LaTeXing): [x]
- [LaTeX-cwl](https://github.com/LaTeXing/LaTeX-cwl): [x]
- [TeXstudio Completion](https://sourceforge.net/p/texstudio/hg/ci/tip/tree/completion/): [x]
- [Imagemagick](https://imagemagick.org/): [x]
    - `brew install imagemagick`
- [ghostscript](https://ghostscript.com/index.html): [x]
    - `brew install ghostscript`
- [Latex-cwl 插件自动补全问题](https://blog.csdn.net/weixin_42465278/article/details/117332092): [x]
- [Sublime Text 4094, latex autocomplete problem](https://github.com/SublimeText/LaTeXTools/issues/1506): [x]

### For Python

- [Anaconda](http://damnwidget.github.io/anaconda/): [x]
- [SublimeREPL](https://github.com/wuub/SublimeREPL): [x]
- [Helium](https://github.com/sschuhmann/Helium): [x]

### For JavaScript

- [js-beautify](https://github.com/beautify-web/js-beautify)
    - `npm install js-beautify`
    - This little beautifier will reformat and re-indent bookmarklets, ugly JavaScript.
    - `Js-beautify.sublime-build`
- [prettier](https://github.com/prettier/prettier)
    - `npm install prettier`
- [JsPrettier](https://github.com/jonlabelle/SublimeJsPrettier)
    - for pretty prettying `json`, `js`, `ts`, `html`, `css`
- [Sublime-HTMLPrettify](https://github.com/victorporof/Sublime-HTMLPrettify): [x] - (**deprecated**)
- [JsFormat](https://github.com/jdavisclark/JsFormat): [x] - (**deprecated**)
- [Chrome Extensions LiveReload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en): [x]
    - This extension is no longer available because it doesn't follow best practices for Chrome extensions.

### For HTML and CSS

- [Emmet.io](https://github.com/emmetio)
    - Emmet is a web-developer’s toolkit for boosting HTML & CSS code writing.
    - [Emmet-sublime-text-plugin](https://github.com/emmetio/sublime-text-plugin)
    - [emmet-sublime](https://github.com/sergeche/emmet-sublime): [x] - (**deprecated**)

### For UML

- [plantuml.com](https://plantuml.com)
    - [Guide](https://plantuml.com/en/guide)
    - [sublime_diagram_plugin](https://github.com/jvantuyl/sublime_diagram_plugin): [x]
    - [PlantUmlDiagrams](https://github.com/evandrocoan/PlantUmlDiagrams): [x]

- [Graphviz](http://graphviz.org/): [x]

### For Terminal

- [Terminus](https://github.com/randy3k/Terminus)

### For Debugging

- [SublimeDebugger](https://github.com/daveleroy/SublimeDebugger): [x]

### For ChatGPT

- [Sublime-Text-ChatGPT](https://github.com/eusonlito/Sublime-Text-ChatGPT): [x]
- [OpenAI-sublime-text](https://github.com/yaroslavyaroslav/OpenAI-sublime-text): [x]

### Others

- [quarto-sublime](https://github.com/quarto-dev/quarto-sublime): [x]
- [ctags](https://github.com/SublimeText/CTags): [x]
