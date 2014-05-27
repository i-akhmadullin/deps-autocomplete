Sublime Text deps-autocomplete
===

Автодополнение для deps.js

![Автодополнение для deps.js](/deps.gif "Автодополнение для deps.js")

Установка
----------------------------------

1. Ctrl+Shift+P → Package Control: Add Repository → https://github.com/i-akhmadullin/deps-autocomplete

2. Ctrl+Shift+P → Package Control: Install Package → deps-autocomplete

3. В *.deps.js файлах будет срабатывать автодополнение, sublime будет определять синтаксис как deps.js

Линтинг с sublimelinter-jscs
----------------------------------
Чтобы линтер проверял файлы deps.js также как и обычные js-файлы, надо расширить `syntax_map` в файле `User/SublimeLinter.sublime-settings`:
```
"syntax_map": {
  "deps.js": "javascript"
},
```
