### using-vscode-with-cupl
Syntax color + build with cupl.exe settings + simulation(planned)

### Files:
- `cupl-syntax-highlight.1.1.7.vsix` - Syntax highlight extension for VS Code. It is provided 'As Is'. Actually, it was pathced from another extension,  so there is a little extra code in it, some incorrect tokens are used, and so on. The main thing is that it works.
- `.vscode` - CUPL build support settings. You can simply put the `.vscode` folder into your workspace or copy some entries to global json files. Before you start working, you should change the path settings in the `cupl` section of this `settings.json`.

### To Do:
- put in order the syntax highlight extension
- add simulation (compile/run/watch) using ASCII|UNICODE pseudographics
- may be write python or C# wrappers to allow using non ASCII symbols in PLD|SI Files


### using-vscode-with-cupl
Подсветка синтаксиса + настройки сборки для cupl.exe + симуляция(планируется)

### Описание файлов:
- `cupl-syntax-highlight.1.1.7.vsix` - Расширение подсветки синтаксиса для VS Code.  Предоставляется "Как есть".  На самом деле оно было сделано путём пропатчивания другого расширения, поэтому присутсвует лишний код, используются некоторые некорректные токены и так далее. Главное, оно работает.
- `.vscode` - Настройки поддержки сборки CUPL. Вы можете просто поместить папку ".vscode" в свою рабочую область или же переместить некоторые записи в глобальные файлы json. Прежде чем начать работать, вам следует изменить настройки пути в разделе "cupl",  приведенного файла "settings.json" .

### В планах (to-do):
- Привести в порядок расширение подсветки синтаксиса.
- Добавить симуляцию (компиляция/запуск/просмотр) используя ASCII|UNICODE псевдографику
- Может быть, реализовать обертку на python или C#, которая позволит использовать не ASCII символы в PLD|SI файлах.

