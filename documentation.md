 * python
   * notebook
     * запуск: в консоли: `ipython notebook`
     * когда запущен: http://localhost:8889/tree
     * cntrl + enter - запустить выделенную ячейку
	 * "+" в тулбаре - новая ячейка
 * markdown
   * ...
 * консоль
   * Формат команды: имя_команды аргумент аргумент ...
   * Описание команды:
     * `<имя_аргумента>` - обязательный аргумент. Пример:
       * `cd <каталог>` - например `cd ~`
     * `[имя_аргумента]` - опциональный аргумент
   * Квотирование (quoting, escaping) аргументов:
     * backslash `\` для всего
       * пример: `echo a\$b`, `echo a\\b`
     * Пробелы в аргументе => обернуть в двойные кавычки
     * ...
   * Базовые команды:
     * `echo <текст>`: вывести текст
   * Более полный пример команды:
     * `NAME1=val1 NAME2=val2 cmd1 ar1 ar2 < in_file  > out_file &`
       * `NAME1=val1` - установить переменную окружения `NAME1` в `val1`
       * `< in_file` - подать файл `in_file` на вход
       * `> out_file` - записать вывод в файл `out_file`
       * `&` - запустить в фоне
 * git
   * git clone <url> - склонировать репозиторий 
   * git init - создать новый репозиторий в текущем каталоге 
   * git add - добавляет файлы в коммит или репозиторий
   * git status - текущее состояние репозитория
   * `git diff ...` - показать разницу
     * `git diff` - показать сделанные незакоммиченные изменения
     * `git diff A B` - показать разницу между A и B
   * `git commit -m <комментарий>` - закоммитить
     * `... -a` - все изменения.


