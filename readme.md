# Git and GitHub Course

Crach Course for Git

Вот некоторые основные команды для работы с Git в терминале (командной строке):

git init: Создает новый локальный репозиторий Git в текущем каталоге.

git clone [URL]: Клонирует удаленный репозиторий на локальную машину. [URL] - URL удаленного репозитория.

git add [file]: Добавляет изменения в файле для последующего коммита. Можно использовать git add . для добавления всех изменений.

git commit -m "[message]": Фиксирует добавленные изменения и создает коммит с сообщением [message].

git status: Показывает текущее состояние репозитория, список измененных, добавленных и неотслеживаемых файлов.

git log: Отображает историю коммитов в репозитории.

git pull: Вытягивает изменения из удаленного репозитория и объединяет их с текущей веткой.

git push: Отправляет коммиты на удаленный репозиторий.

git branch: Показывает список всех веток в репозитории. Звездочка (\*) указывает на текущую ветку.

git checkout [branch]: Переключается на указанную ветку.

git merge [branch]: Сливает указанную ветку с текущей веткой.

git remote -v: Показывает список удаленных репозиториев.

git remote add [name] [URL]: Добавляет новый удаленный репозиторий с именем [name] и URL [URL].

git rm [file]: Удаляет файл из индекса и рабочей директории.

git diff: Показывает различия между рабочим деревом и индексом.

Это только небольшой список основных команд Git. С Git связано много других команд и опций, их полный список и справку по каждой команде можно получить, запустив git help в терминале, например git help commit для получения справки по команде git commit.

…or create a new repository on the command line
echo "# git-course" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Cryptokrupt/git-course.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Cryptokrupt/git-course.git
git branch -M main
git push -u origin main
