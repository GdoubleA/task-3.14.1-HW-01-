# Инструкция по работе с GIT
 

 LICENSE: [MIT](license.md)

![git-logo](./img/1920px-Git-logo.svg.png)
---



**Git** (*произносится «гит»*) — это бесплатная распределенная система управления версиями с открытым исходным кодом, предназначенная для быстрой и эффективной обработки любых проектов, от небольших до очень крупных. Проект был создан [Линусом Торвальдсом](https://ru.wikipedia.org/wiki/%D0%A2%D0%BE%D1%80%D0%B2%D0%B0%D0%BB%D1%8C%D0%B4%D1%81,_%D0%9B%D0%B8%D0%BD%D1%83%D1%81) для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает [Джунио Хамано](https://ru.wikipedia.org/wiki/%D0%A5%D0%B0%D0%BC%D0%B0%D0%BD%D0%BE,_%D0%94%D0%B7%D1%8E%D0%BD).

**Git** легко освоить , он занимает мало места и обладает молниеносной производительностью . Он превосходит инструменты SCM, такие как Subversion, CVS, Perforce и ClearCase, благодаря таким функциям, как дешевое локальное ветвление , удобные промежуточные области и несколько рабочих процессов .


Среди проектов, использующих Git — ядро [Linux](https://ru.wikipedia.org/wiki/%D0%AF%D0%B4%D1%80%D0%BE_Linux), [Swift](https://ru.wikipedia.org/wiki/Swift_(%D1%8F%D0%B7%D1%8B%D0%BA_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)), [Android](https://ru.wikipedia.org/wiki/Android), [Drupal](https://ru.wikipedia.org/wiki/Drupal), [Cairo](https://ru.wikipedia.org/wiki/Cairo), [GNU Core Utilities](https://ru.wikipedia.org/wiki/GNU_Coreutils), [Mesa](https://ru.wikipedia.org/wiki/Mesa_3D), [Wine](https://ru.wikipedia.org/wiki/Wine), [Chromium](https://ru.wikipedia.org/wiki/Chromium), [Compiz Fusion](https://ru.wikipedia.org/wiki/Compiz_Fusion), [FlightGear](https://ru.wikipedia.org/wiki/FlightGear), [jQuery](https://ru.wikipedia.org/wiki/JQuery), [PHP](https://ru.wikipedia.org/wiki/PHP), [NASM](https://ru.wikipedia.org/wiki/NASM), [MediaWiki](https://ru.wikipedia.org/wiki/MediaWiki), [DokuWiki](https://ru.wikipedia.org/wiki/DokuWiki), [Qt](https://ru.wikipedia.org/wiki/Qt), ряд дистрибутивов [Linux](https://ru.wikipedia.org/wiki/Linux).

---
## Команды GIT:
1. [git config](./config.md)
2. [git init](./init.md)
3. [git add .](./add.md)
4. [git commit](./commit.md)
    - [git commit -a](./commit-a.md)
    - [git commit -m "commit message"](./commit-m.md)
    - [git commit -am "commit message"](./commit-am.md) 
    - [git commit --amend](./commit--amend.md)
5. [git clone](./clone.md)
6. [git remote](./remote.md)
7. [git fetch](./fetch.md)
8. [git merge](./merge.md)
9. [git pull](./pull.md)
10. [git push](./push.md)
11. [git status](./status.md)
12. [git log](./log.md)
13. [git show](./show.md)
---

## Краткая история Git.
Как и многие вещи в жизни, **Git** начинался с капелькой творческого хаоса и бурных споров.

Ядро Linux — это достаточно большой проект с открытым исходным кодом. Большую часть времени разработки ядра Linux (1991–2002 гг.) изменения передавались между разработчиками в виде патчей и архивов. В 2002 году проект ядра Linux начал использовать проприетарную децентрализованную СКВ BitKeeper.

В 2005 году отношения между сообществом разработчиков ядра Linux и коммерческой компанией, которая разрабатывала BitKeeper, прекратились, и бесплатное использование утилиты стало невозможным. Это сподвигло сообщество разработчиков ядра Linux (а в частности Линуса Торвальдса — создателя Linux) разработать свою собственную утилиту, учитывая уроки, полученные при работе с BitKeeper. Некоторыми целями, которые преследовала новая система, были:

- Скорость

- Простая архитектура

- Хорошая поддержка нелинейной разработки (тысячи параллельных веток)

- Полная децентрализация

- Возможность эффективного управления большими проектами, такими как ядро Linux (скорость работы и разумное использование дискового пространства)

С момента своего появления в 2005 году, **Git** развился в простую в использовании систему, сохранив при этом свои изначальные качества. Он удивительно быстр, эффективен в работе с большими проектами и имеет великолепную систему веток для нелинейной разработки.

---
>I'm an egotistical bastard, so I name all my projects after myself. First Linux, now git. 
>>Я эгоистичный ~~ублюдок~~, и поэтому называю все свои проекты в честь себя. Сначала Linux, теперь git.

*Линус Торвальдc*

---
GIT logo by Jason Long. http://git-scm.com/downloads/logos, license: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)


