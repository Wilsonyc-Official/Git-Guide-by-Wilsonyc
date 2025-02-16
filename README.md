# Руководство пользования Git для новичков от Wilsonyc

## Введение
### Здесь мы рассмотрим что такое Git и для чего он нужен

Git – это система контроля версий которая позволяет разработчикам отслеживать изменения в коде, управлять версиями проектом и сотрудничать с другими разработчиками.
Зачем нужен Git:
1.	Управлять версиями: Git позволяет разработчикам отслеживать изменения в коде и управлять версиями проекта, что особенно важно в больших и сложных проектах.
2.	Сотрудничество: Git упрощает совместную работу над проектами, позволяя нескольким разработчикам вносить изменения и интегрировать их в общий код
3.	История изменений: Git сохраняет полную историю изменений, что позволяет разработчикам анализировать, как и почему были внесены изменения, и при необходимости откатываться к предыдущим версиям.
4.	Безопасность: Git позволяет создавать резервные копии кода и восстанавливать его в случае потери данных или ошибок.
5.	Гибкость: Git поддерживает различные рабочие процессы и стратегии разработки что позволяет командам адаптировать его под свои нужды

## Установка Git
### Здесь мы поэтапно установим Git

Для загрузки Git переходим по этой ссылке: https://git-scm.com/downloads

Затем выбираем свою OC в моем случае это Windows затем выбираем разрядность системы в моем случае 64 bit

После скачки файла, открываем его

Шаг №1

![step1](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-03.jpg)

Шаг №2

![step2](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-17.jpg)

Шаг №3

![step3](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-22.jpg)

Шаг №4

![step4](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-26.jpg)

Шаг №5

![step5](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-30.jpg)

Шаг №6

![step6](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-34.jpg)

Шаг №7

![step7](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-37.jpg)

Шаг №8

![step8](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-40.jpg)

Шаг №9

![step9](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-44.jpg)

Шаг №10

![step10](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-47.jpg)

Шаг №11

![step11](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-51.jpg)

Шаг №12

![step12](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-53.jpg)

Шаг №13

![step13](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-38-57.jpg)

Шаг №14

![step14](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Download_ScreenShots/photo_2025-02-16_23-39-00.jpg)

## Основные комманды
### Здесь мы разберем основные комманды для использования Git
### 1.	Настройка Git

1. Устанавливает ваше имя для коммитов: Git config –global user.name «Ваше имя»

2. Устанавливает ваш email для коммитов: Git config --global user.email "ваш Email"

3. Проверка глобальных настроек Git: Git config –global –list

![git_config](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20config.jpg)

---
### 2.	Создание и клонирование репозитория
1. Перейти в репозиторий: cd «Путь репозитория на вашем ПК»

2. Просмотр папок в репозитории: ls

3. Инициализирует новый Git-репозиторий в текущей директории:Git init 

![git_init](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20init.jpg)

4. Копирует удаленный репозиторий по указанному URL:Git clone url

![git_clone](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20clone.jpg)

----
### 3.	Основные операции с файлами

1. Добавляет изменения в текущей директории определённого файла в индекс: git add <файл>

![git_add_name](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20add%20Test.jpg)

2. Добавляет все изменения в текущей директории в индекс: git add .

![git_add_all](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20add%20..jpg)

3. Создает новый коммит с казанным сообщением: git commit -m «Сообщение коммита»

![git_commit](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20commit.jpg)

4. Показывает текущее состояние репозитория, включая изменения файлы в индексе: git status

![git_status](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20status.jpg)

5. Показывает изменения между рабочей директорией и индексом: git diff

![git_diff](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20diff.jpg)

----
### 4.	Работа с ветками

1. Показывает список всех веток в репозитории: git branch

![git_branch](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20branch.jpg)

2. Создает новую ветку с казанным именем: git branch <имя ветки>

![git_branch_branch](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20branch%20branch.jpg)

3. Переключает на указанную ветку: git checkout <имя_ветки>

![git_checkout](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20checkout%20branch.jpg)

4. Создает новую вутку и сразу переключается на неё: git checkout -b <имя_ветки>

![git_checkout_hypertxt](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20checkout%20-b%20hypertxt.jpg)

---
### 5. Слияние и удаление веток

1. Сливает указанную ветку с текущей веткой: git merge <имя ветки>

![git_merge_branch](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20merge%20branch.jpg)

2. Удаляет указанную ветку (если она слита): git branch -d <имя_ветки>

![git_branch_d_branch](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20branch%20-d%20branch.jpg)

----
### 6.	Работа с удаленными репозиториями

1. Для добавления удаленного репозитория: git remote add <имя> url

![git_renite_add](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20remote%20add.jpg)

2. Показывает список удаленных репозиториев: git remote -v

![git_remote_v](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20remote%20-v.jpg)

3. Получает изменения из удаленного репозитория и сливает их с текущей веткой: git pull <имя> <ветка>

![git_pull_name](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20pull%20origin.jpg)

---
### 7. Просмотр истории

1. Показывает историю коммитов: git log

![git_log](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20log.jpg)

2. Показывает историю коммитов в сокращенном виде: git log –oneline

![git_log_oneline](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20log%20--online.jpg)

---
### 8. Отмена изменений

1. Отменяет изменения в указанном файле (возвращает к последнему коммиту): git checkout -- <файл>

![git_checkout__Test](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20checkout%20--%20Test.jpg)

2. Убирает файл из индекса, но оставляет изменения в рабочей директории: git reset <файл>

![git_reset_command](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20reset%20command.jpg)

3. Убирает все изменения в рабочей директории и индексе, возвращая к последнему коммиту: git reset –hard

![git_reser__hard](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20reset%20--hard.jpg)

---
### 9.	Работа с тегами
1. Показывает список тегов: git tag

![git_tag](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20tag.jpg)

2. Создает новый тег: git tag <имя_тега>

![git_tag_flag](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/git%20tag%20flag.jpg)

---
### 10. Открытие файла в Visual Studio Code
Чтобы открыть файлы в Visual Studio Code для начала убедитесь что VS Code установлен

затем в Git введите: code <Название файла>

![code_readme](https://github.com/Wilsonyc-Official/Git-Guide-by-Wilsonyc/blob/main/Other/Command_Screenshot/code%20Readme.jpg)

Чтобы открыть предпросмотр нажимаем сочетание клавиш Ctrl+Shift+V

## Заключение

Если вам некомфортно работать с командной строкой, вы можете использовать графические интерфейсы для Git. Такие как:

•	GitHub Desktop: Удобный и интуитивно понятный интерфейс для работы с GitHub

•	GitKraken: Довольно мощный инструмент с красивым и понятным графическим интерфейсом

Git – это мощный инструмент для управления версиями, и его освоение может значительно улучшить ваш рабочий процесс. 
