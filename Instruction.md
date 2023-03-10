# __Начальная работа с системой контроля версий__

## __Основные комманды git:__
![Git_logo](resources/git_logo.png)

---

* __git --version__ - _комманда для проверки версии git_

![git_version](resources/Git_version.jpg)

* __git init__ - _инициализируем пустой репозиторий_

* __git status__ - _проверяем текущее состояние файлов_

* __git add имя_файла_с_расширением__ - _добавляем версионность файлу_

* __git add .__ - _добавляем версионность всем файлам в папке_

* __git commit -m "Сообщение"__ - _команда для фиксации изменений файлов_

* __git commit -am "Сообщение"__ - _фиксация изменений с комментарием (не требует git add)_

* __git diff__ - _вывод изменений на текущий момент, по отношению к последнему коммиту_

* __git log__ - _вывод истории коммитов в хронологическом порядке_

* __git checkout хэш_коммита__ - _переход между изменениями_

* __git chekout master__ - _возврат к текущему состоянию_

---

## __Оформление шрифтом Mardown__  
![Markdown_logo](resources/Markdown_logo.jpg)

---

<p style="text-align: center;">Для жесткого переноса строки - вконце строки нажмите два раза пробел и Enter</p>

---

<p style="text-align: center;">ВЫДЕЛЕНИЕ ТЕКСТА</p>

---

* Для выделения текста __Полужирным__ шрифтом обрамите его символами двойных звездочек ("**") или двойным нижним подчёркиванием ("__")  

* Для выделения теста _Курсивом_ обрамите его символами звездочек ("*") или нижним подчёркиванием ("_")  

* Для выделения текста **_Полужирным курсивом_** совместите сочетания звездочек ("*") и нижних подчеркиваний ("_")

---

<p style="text-align: center;">ЗАГОЛОВКИ</p>

---

* __Заголовки__ оформляются символом __#__
    >Уровень заголовка определяется по количеству начальных символов:
    >>"#" - Первый уровень заголовка  
    >>"##" - Второй уровень заголовка и т.д.  
  
* __Выделение заголовков__ с помощью подчеркивания производится знаками равенства __"="__ в случаем, если заголовок __первого уровня__, и дефисами __"-"__ в случае, если заголовок второго уровня.
    >Заголовок первого уровня  
    ==================  
    Заголовок второго уровня  

---

<p style="text-align: center;">ЦИТАТЫ</p>

---

* Для обозначения цитат в языке Markdown используется знак «больше» __(«>»)__. Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа.

    >Это пример цитаты  

* Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Для их разметки используются дополнительные уровни знаков цитирования (">").  
Уровень цитаты определяется по количеству начальных символов ">", ">>" и т.д.
    >Цитата __первого__ уровня  
    >>Цитата __второго__ уровня _(цитата внутри цитаты)_  
    >>>Цитата __третьего__ уровня и _так далее_  

* При вставке цитат в элементы списка важно учитывать, что элементы списка должны находиться на одном уровне, а цитаты должны указываться с отступом. В случае, если правило с единым уровнем списка не соблюдается, следующий после цитаты элемент списка будет автоматически нумероваться цифрой «1.». Кроме того, при необходимости в список можно вставить исходный код. В этом случае его нужно писать с двойным отступом – 8 пробелов или 2 символа табуляции.

---

<p style="text-align: center;">ССЫЛКИ</p>

---

* Markdown поддерживает два стиля оформления ссылок:  
    1. Гиперссылка, с немедленным указанием адреса (внутритекстовая);
    >[Пример](https://google.com/ "подсказка, при наведении курсора")
    2. Гиперссылка, подобная сноске.  
    >_Пример:_ https://google.com/  

---  

<p style="text-align: center;">Кодовые фрагменты строк</p>  

---  

Чтобы отметить фрагмент строки, содержащий `код`, необходимо окружить его обратными апострофами __" ` "__. При использовании кодовых фрагментов строк текст будет отображаться в виде моноширинного шрифта. В отличие от блоков кода, кодовый фрагмент позволяет поместить код внутрь обычного абзаца текста.  
>Пример: `code`  
---  
  
<p style="text-align: center;">Источники информации, которые использовались при написании данной инструкции: </p>

1. https://gist.github.com/Jekins/2bf2d0638163f1294637#Images
2. http://konvut.github.io/k50articles/
3. https://code.visualstudio.com/Docs/languages/markdown  
    [перевод](https://translated.turbopages.org/proxy_u/en-ru.ru.ce99d1d5-63d55739-75a18b32-74722d776562/https/code.visualstudio.com/Docs/languages/markdown#_find-all-references-to-headers-and-links)  
