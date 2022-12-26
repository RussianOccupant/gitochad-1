GitHub



***For started job with git-file enter commands:*** 

1. git init (for folder initialization) 
2. git add (name folder) (for save new data in folder) 
3. git commit -m 'bla-bla' (for added a comment and save changes) 

**These commands are always written after changes** 

**Аs the beginning of one of the prayers** 

* **git diff** (show difference between commits) 
* **git log** (To view all existing commits) 
* **git log --oneversion** (Тo view all existing commits without too much information) 
* **git checkout** (to go to a specific branch/commit) 
* **git branch** (show all branches) 
* **git merge (name branch)** (merging two branches (the branch we are on will merge with the branch specified in the command)) 
* **git merge -d ""** (deleting a branch) 
* **git revert (hash commit)** (deleting a commit) 
* **git status** (status check) 

***Work with remote repository***

1. Заходим на GITHUB, нажимаем на "+" в правом верхнем углу, приказываем создать новый репозиторий 
2. Создаем репозиторий комментируем его, вводим описание. 
3. Нажимаем created new repository и вводим в терминал следующие команды: 
* **git remote add** - Добавляем нашу папку в удаленный репозиторий 
* **git branch -M (название основной ветки)** - указываем главную ветку 
* **git push** - Отправляем наши данные на удаленку Work with remote repository: 
* **git push** - Send information in remote repository 
* **git pull** - Send information in local repository from remote repository 

Work on remote repository: 
1. Открываем файл 
2. Нажимаем на карандаш 
3. Жмем commit changes 

Импорт репозитория: 

1. Находим какой-либо удаленный репозиторий 
2. чтобы клонировать удаленный репозиторий - нажимай кнопку Fork -> копируем ссылку данного репозитория -> открываем редактор кода и вставляем ссылку -> редактируем, вводим команду **git push** -> обновляем удаленный репозиторий 

Уведомление автора оригинальной работы (удаленного репозитория): 
1. нажимаем pill reqests -> new pull request/view pull reqest -> created new request