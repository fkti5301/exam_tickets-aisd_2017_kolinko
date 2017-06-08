# Ответы на экзаменационные вопросы [АиСД, Колинько, 2017]

Тут будут собраны ответы на все экзаменационные вопросы по дисциплине "Алгоритмы и структуры данных" за 4-й семестр.

Преподаватель: Колинько П.Г.
Год: 2017

[Онлайн версия](https://fkti5301.gitbooks.io/exam_tickets-aisd_2017_kolinko/content/)



## Правила:
Чтобы начать заполнять ответы, требуется:

1. Установить клиент Git *(ссылки ниже)*

2. Настроить SSH и подключить к своему аккаунту *(ссылки ниже)*

3. Клонировать к себе данный репозиторий:
   ```
   git clone git@github.com:fkti5301/exam_tickets-aisd_2017_kolinko.git
   ```

4. Создать/заполнить файл X.md со своим вопросом и кинуть его в папочку tickets. Если создаёте пустой файл и отправляете его в репозиторий, значит, вы заняли этот вопрос, и можете спокойной его заполнять, будучи уверенными, что никто его не возьмёт.

5. Обновить SUMMARY.md, добавив туда ссылку на новый файл в виде строки:
   ```
   * [Вопрос #: текст вопроса](tickets/#.md)
   ```

6. Стянуть изменения:
   ```
   git pull
   ```

7. Закоммитить его:
   ```
   git add -A .
   git commit -m "ticket X: [Название коммита. English only]"
   ```
   Примеры названий коммитов: "ticket 1: Create ticket", "ticket 14: Complete ticket", "ticket 40: Fix typo", "ticket 31: Add more info".

8. И отправить в репозиторий:
   ```
   git push
   ```

Для тех, кто собирается юзать приложение. У гитбука есть ограничение на количество пользователей одного репозитория, поэтому, чтобы работать всем вместе, делаем следующее: GitBook Editor -> Open -> [Выбираем папку с репозиторием]

Приложение с точки зрения git-а не очень удобное. Тут полностью пропущена стадия staged. Как только нажимаете кнопочку "Save", происходит коммит. Поэтому, чтобы не засорять репозиторий делайте следующие вещи:

* Сохраняйтесь только когда действительно уверены, что готовы отправить это в репозиторий в виде коммита.

* Отключите в настройках автогенерацию названия Settings -> Git -> Automatically generate commit... -> Off.

Пуш осуществляется нажатием кнопки Publish. На данный момент их редактор не поддерживает SSH, поэтому, если хотите пушить с помощью GUI, настраивайте через HTTPS.



## Пример
[Пример](https://fkti5301.gitbooks.io/exam_tickets-aisd_2017_kolinko/content/tickets/0.html) заполнения билета:
```
# Вопрос 0: Тут пишем вопрос
А тут - ответ. Изи.
Расписываем подробно. Источники - Интернет, метода, конспекты, другие файлы. Главное, чтобы было по теме и информативно.

```cpp
int main() {
	/* Тут можно вводить какой-нибудь код. Для подсветки синтаксиса используем ```cpp */

	cout << "Hello, World!" << endl;
}

```

А вот так выглядят формулы: $$ x = e^{a+b} $$
```



## Полезные ссылки
**Git:**

[Клиент Git](https://git-scm.com/download/win)

[Гайд по Git](https://githowto.com/create_a_project)

[Маленькая книжка-мануал](https://git-scm.com/book/ru/v1)


**Настройка SSH:**

[Генерация SSH ключа](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

[Добавление ключа в аккаунт](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

[Проверка работоспособности](https://help.github.com/articles/testing-your-ssh-connection/)


**Markdown:**

[Кратко о синтаксисе](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)


**GitBook:**

[Доки](https://gitbookio.gitbooks.io/documentation/content/index.html)


**KaTeX:**

[Вики](https://github.com/Khan/KaTeX/wiki)

[Использование](https://gitbookio.gitbooks.io/documentation/content/format/math.html)

