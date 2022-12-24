# Руководство по GIT
1. **git --global user.name <Ваше имя> и --global user email <адрес_почты>** - представляемся гиту;

2. **git init** - иницилизация (создание) репозитория;

3. **git add <имя_файла>** - добавляет конкретный файл в коммит;

4. **git add .** - добавляет все файлы дериктории в коммит;

5. **git status** - проверка статуса ветки;

6. **git commit -m "<коментрарий>"** - фиксация состояния с указанием коментария;

7. **git diff** - просмотр разницы текущего и зафиксированного файла (красный удаленный, зелёный добавленный);

8. **git log** - список commit; 

9. **git checkout <имя_ветки>**- переход между ветками;

10. **git branch** - показывает существующие ветки проекта (прим. зелённым и звездочкой "*" отображается где мы находимся);

11. **git branch <имя_ветки>** - создаёт ветку;

12. **git checkout -b <имя_ветки>** - создаёт ветку и автоматически переходит в неё;

13. **git merge** - "слияние" веток;

14. **git reset** - отмена изменений;

15. **git revert** - отменяет изменения, записанные только одним коммитом. Она не откатывает проект к более раннему состоянию, удаляя все последующие коммиты, как это делает команда **git reset**;

16. **git clone URL** - создание копии удалённого репозитория; 

17. **git push** - выгрузка;

18. **git pull** - загрузка;

19. **git fetch** - загружает коммиты, файлы и ссылки из удалённого репозитария:
![Вся правда про GIT](https://www.meme-arsenal.com/memes/e980b8cf8b3273929c68451d698d5d99.jpg)
![Ещё немного про GIT](https://i.imgflip.com/lrihf.jpg)