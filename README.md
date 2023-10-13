# HPMOR Adventure Creator

## Совместная работа над проектом

Игра разрабатывается с использованием [Adventure Creator](https://adventurecreator.org/). В этом репозитории хранятся файлы assets, из которых собирается проект. Чтобы это работало, используются ActionList assets (их нужно указывать в качестве Actions Source везде, где возможно).

**Видео-гайд [доступен по ссылке](https://drive.google.com/file/d/1ECYfyWU2N2OVHYGxEtiH1AIWXwpTc6L2/view?usp=drivesdk)**.

### Система контроля версий git

Источники для старта:

- [Наш видео-гайд!](https://drive.google.com/file/d/1ECYfyWU2N2OVHYGxEtiH1AIWXwpTc6L2/view?usp=drivesdk)
- [Git за полчаса: руководство для начинающих](https://proglib.io/p/git-for-half-an-hour)
- [Git for Windows](https://gitforwindows.org/)

Как мы работем:

- Перед там как начать работать, сделайте `git pull` чтобы получить последние изменения
- Для добавления сцены / фичи / whatever, создавайте ветку: `git checkout -b new_feature`
    - Для переключения на ветку: `git checkout new_feature` (или `git checkout master` для переключения на основную ветку)
    - Чтобы создать ветку также можно использовать `git branch new_feature` и потом переключиться на нее
- После того как вы закончили работу над фичей, сделайте `git add .` чтобы добавить все изменения в коммит
- Сделайте `git commit -m "Some meaningful description"` чтобы создать коммит
- Сделайте `git push` чтобы отправить изменения на сервер
- Затем Леша сливает изменения, разрешает конфликты, тестирует
- Позже при необходимости сделаем ветку prod, в которую будут попадать только проверенные изменения