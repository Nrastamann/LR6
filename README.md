# LR6
Лабораторная работа №6

*__Цель лабораторной работы:__ изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.*

__Клонирование репозитория__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_1.jpg)

__Добавление файла__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_12.jpg)

__Подтягивание изменений в локальную ветку__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_2.jpg)

__История операций ветки мастер__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_3.jpg)

__История операций ветки branch1__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_4.jpg)

__Merge conflict__

Для решения конфликта было принято решение о слиянии файлов из обоих веток в один общий, после была добавлена еще одна строчка. В качестве визуального редактора был использован Visual studio code.

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_13.jpg)

__Слияние веток__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_5.jpg)

__Удаление ветки__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_6.jpg)

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_11.jpg)

__Откат коммита__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_9.jpg)

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_10.jpg)

__Создание ветки для отчета__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_14.jpg)

__Логи комманд__

```
cd githubReps/ - команда перехода в директорию githubReps
git clone https://github.com/Nrastamann/LR6 - команда клонирования репозитория на компьютер
git pull - подтягивание изменений в локальную ветку
git log - получение изменений текущей ветки
git checkout branch1 - смена текущей ветки на branch1
git log branch1 - получение изменений ветки branch1
git merge branch1 - слияние с веткой branch1
git commit -m "Merge branch 'branch1'" - коммит об успешном слиянии
git branch -d branch1 - удаление локальной ветки
git push -d origin branch1 - удаление remote ветки
git add . - добавление всех файлов в коммит
git status - статус репозитория
git commit -m "Added file to change it later" - коммит о добавлении файла
git add FileWithChanges.txt - добавление в коммит конкретного файла
git status - статус репозитория
git commit -m "Changed file file with changes" - коммит об изменении файла
git push origin master - пуш коммитов в мастер
git reset --hard HEAD~1 - откат коммита
git branch report - создание ветки для отчета
git switch report - смена ветки на ветку отчета
```
__История операций__

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/screens/Screenshot_1.jpg)

__Вывод:__  Я изучил базовые возможности системы управления версиями, получил опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.