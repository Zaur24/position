# памятка git + github

## проверка наличие git
ls -la

### инициализация git (main или master) 
git init

#### в случае промоха папки, удаляем git      !!!!! ( rm -rf /      !!!!!)может ПОЛНОСТЮ УДАЛИТЬ ВСЮ ДИРЕКТРОИЮ!!!!!!!!
rm -rf .git/

##### Индексация файла перед коммитом
git add .

###### проверить статус репозитория
git status

###### Сохряняем изменение в истории git
git commit -m "Commentirovat"

###### посмотреть историю коммитов
git log

######  проверка пользователя 
git config --list | grep user

### изменить пользователя
git config --global user.name "Zaur Hasanov"

#### изменить эмаил(почту)
git config --global user.email 24zaur@rambler.ru