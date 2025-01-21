Файл .gitignore нужен для того, чтобы указать Git, какие файлы и папки он должен игнорировать при отслеживании изменений.

Коротко говоря, .gitignore исключает определенные файлы и папки из истории Git, чтобы они не были добавлены в репозиторий и не вызывали лишние конфликты.

Команды использованные в для отчета:
cd C:/Users/igork/intership-todo
 mkdir strudent_77
 echo "Калугин Игорь Александрович" >> README.md
touch .gitignore
git remote add origin https://github.com/Igoriao52/internship-todo.git
git add README.md
git add .gitignore
git commit -m "Вальер Коммит"
git push -u origin master
touch got_bash_command_md
git add got_bash_command.md
git commit -m "Коммит отчета"
git push -u origin master
