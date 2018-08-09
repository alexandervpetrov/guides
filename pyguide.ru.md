
# Python Development Guide

*Здесь описаны и документированы рекомендации и соглашения по программированию на Python.
За исключением отдельных примеров тут нет слишком специфичной информации - это общие
рекомендации и философия разработки. Есть надежда что документирование таких вещей
поможет команде быть более сбалансированной и поможет эффективнее поддерживать в коде
ряд ценностей важных для эволюции проекта.*


Самыми базовыми вещами в плане стиля и вкуса для любого программиста на Python
являются [The Zen of Python (PEP 20)][pep20] и [Style Guide for Python Code (PEP 8)][pep8] -
они обязательны к прочтению. Абсолютно весь Python-код на проекте **должен** проходить
проверку на соответствие PEP 8 стандартной утилитой [pycodestyle][pycodestyle]
в режиме проверки всех ошибок за исключением ограничения на длину строки (`--ignore=E501`).

Основой для соглашений по стилю кодирования является [Google Python Style Guide][googlepyguide],
его необходимо прочитать, если в данной статье прямо что-то не оговорено,
то значит по умолчанию берётся соглашение из этого руководства Гугла.

Также грамотные и разумные вещи можно почитать в [The Hitchhiker’s Guide to Python][hitchhiker].


[pep20]: https://www.python.org/dev/peps/pep-0020/
[pep8]: https://www.python.org/dev/peps/pep-0008/
[pycodestyle]: https://pypi.org/project/pycodestyle/
[googlepyguide]: https://github.com/google/styleguide/blob/gh-pages/pyguide.md
[hitchhiker]: https://docs.python-guide.org/
