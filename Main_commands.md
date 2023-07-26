1. **git add** - *используется для добавления всех файлов или единственного файла (если дополнить команду именем файла) для сборки последующего коммита.*

    `git add "filename"`

2. **git commit** - *используется для сборки всех существующих **git add**-ов в контейнер для последующей отправки в репозиторий, обычно используется с параметром **-m** , например:*

    `git commit -m "my first commit"`

    но есть и другие параметры:

 * **-v** - *добавляет к комментарию коммита информацию о изменения.* 
  * **-a** - *автоматически добавляет все изменённые файлы в коммит.*
 
    *испрользование команды без параметра приведёт к вводу комммита последующей командой*

3. **git push** - *отправляет подготовленный коммит в репозиторий*