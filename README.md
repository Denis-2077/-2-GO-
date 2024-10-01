# .GO
git config --global user.name “Денис”
git config --global user.email “denis.stormy@gmail.com”


git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main
git config --global core.autocrlf true
git config --list

git init # инициализация
git add . # добавить все файлы
git commit -m "Проект GO" # сделать коммит

git status # текущий статус
git diff # текущие изменения
git diff --color-words более развернуто
git checkout . # последний коммит# -2-GO-
