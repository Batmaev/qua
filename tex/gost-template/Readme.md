# ГОСТ 7.32-2017 LaTeX Template

Оформление выпускной квалификационной работы регламентируется ГОСТ 7.32-2017
"Отчёт о научно-исследовательской работе".

В этой папке находится преамбула и другие части LaTeX-документа для соответствия этому ГОСТу.

Я с незначительными изменениями скопировал всё из репозитария [github.com/vpunch/gost732](https://github.com/vpunch/gost732). Спасибо [@vpunch](https://github.com/vpunch) за проделанную работу!

Список команд:

- `\structel{НАЗВАНИЕ}` - создать структурный элемент,
- `\hidedstructel{НАЗВАНИЕ}` - то же, но не попадает в сожержание,
- `\annex{Название}` - создать приложение,
- `\sect{Название}` - создать раздел,
- `\subsect{Название}` - создать подраздел,
- `\parag Содержание` - создать пункт,
- `\subparag Содержание` - создать подпункт,
- окружение `asblist` - создать список,
- `\fig[0.8]{path/to/file}{Название}` - вставить рисунок,
- `\lst{path/to/file}{Название}` - вставить листинг из файла,
- окружение `codepiece` - вставить листинг из документа,
- `tbl{метка}{Название}{N{3cm}N{3cm}}` - создать простую таблицу,
- `thead<>[2]{6cm+2\tabcolsep}{Название}` - создать заголовок таблицы,
- `tabcode` - вставить код в таблицу,
- `longtbl{метка}{Название}{N{1cm}N{2cm}N{3cm}}` - создать длинную таблицу,
- `\showbib` - вывести раздел с источниками.

Изменения, которые внёс я, касаются отступов, которые не были заданы в исходном файле, из-за чего файл не компилировался.
