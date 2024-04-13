# verygood-bitrix-support-2024
 Техническая поддержка сайтов  на 1C Битрикс Лендинг

## Ссылка на проект https://lavrrusha.github.io/verygood-bitrix-support-2024/

## Общее

Ссылка на макет: https://www.figma.com/file/HGvEhmtEBX3bkmjTcH6Rjj/very-good-(%D0%9E%D0%BB%D0%B5%D1%81%D1%8F)?type=design&node-id=0%3A1&mode=design&t=SGKbQZuIE8mjh6zH-1


Тип Верстки: Адаптивная, с использованием Flexbox или Grid.
Разрешения экрана:

- Desktop (1920px);
- Laptop (1024px);
- Tablet (768px);
- Mobile (375px).

Шрифты: Использовать шрифты Inter согласно макета, с поддержкой кириллицы, подключить локально - из папки проекта. Использовать только Woff2 формат.
Иконки должны быть в формате SVG.

Цвета: Указать цветовую палитру в HEX или RGB.
Интерактивность: Описать поведение элементов при наведении, нажатии (hover, active, focus).

## Как будем работать над проектом

Шаг 1: сделай форк проекта в свой репозиторий и выполни все задания.
затем отправь изменения на мой репозиторий в основную ветку
Шаг 2: я проверю и приму, или верну на доработку.
когда сделаешь все верно - я приму изменения и напишу новое задание.

## Если запуталась как делать форк или пушить в основную ветку

В GitHub Desktop, процесс создания форка и внесения изменений в основную ветку проекта состоит из нескольких шагов. Вот как ты можешь это сделать:

### Шаг 1: Создание форка проекта

Чтобы создать форк проекта на GitHub, сначала нужно сделать это через веб-интерфейс GitHub, так как GitHub Desktop не предоставляет функциональность для создания форка напрямую.

Перейди по ссылке https://github.com/yurkaronin/verygood-bitrix-support-2024.
В правом верхнем углу страницы, нажми кнопку "Fork". см скрин 
Это создаст копию репозитория в твоём аккаунте на GitHub.

### Шаг 2: Клонирование форка с помощью GitHub Desktop

Теперь, когда у тебя есть форк в твоём аккаунте GitHub, ты можешь клонировать его на свой компьютер с помощью GitHub Desktop. 'help\как сделать форк.png'

Открой GitHub Desktop.
В меню выбери File -> Clone repository.
В появившемся окне перейди на вкладку URL.
Вставь URL своего форка (он должен быть вида https://github.com/ВАШ_ЛОГИН/verygood-bitrix-support-2024).
Выбери, куда  хочешь клонировать репозиторий на своём компьютере, и нажми "Clone". если что не нашла см скрин 'help\как клонировать репозиторий.png'

### Шаг 3: Внесение изменений в проект

Теперь ты можешь вносить изменения в проект, используя свою любимую среду разработки или текстовый редактор.

Открой папку проекта на вашем компьютере.
Внеси необходимые изменения в файлы.
Сохрани изменения.

### Шаг 4: Фиксация изменений (Commit) и отправка их в свой форк на GitHub

Открой GitHub Desktop и выбери репозиторий, в котором ты работала.
В разделе "Changes" ты увидишь список всех несохранённых изменений. Выбери файлы, которые хочешь зафиксировать.
Введи краткое и понятное сообщение коммита, описывающее внесённые изменения.
Нажми кнопку "Commit to [название твоей ветки]" для фиксации изменений.
После коммита нажми кнопку "Push origin", чтобы отправить изменения в свой форк на GitHub.

### Шаг 6: Создание Pull Request в оригинальный репозиторий (мне)

Перейди в свой форк на GitHub в веб-браузере.
Нажми на кнопку "Pull requests" в твоём форке и затем "New pull request".
Убедись, что базовая ветка в оригинальном репозитории выбрана корректно (обычно это main или master), а сравниваешь ты свою ветку, в которую ты внесла изменения.
Нажми "Create pull request".
Введи название и описание для твоего Pull Request, чтобы объяснить, какие изменения ты сделала и почему.
Если всё готово, нажми "Create pull request" ещё раз.
Теперь твой Pull Request будет отправлен на рассмотрение. Владелец оригинального репозитория (в данном случае yurkaronin) сможет просмотреть твои изменения, оставить комментарии, запросить дополнительные доработки или принять их, смерджив с основной веткой проекта.


## Задание 1

1. Подключить основной стилевой файл из папки проекта
2. Подключить основной файл скриптов из папки проекта
3. В стилевом файле css\base\_fonts.scss подключить только те файлы шрифтов, которые фигурируют в макете. пример подключения оставил в комментариях. У шрифтов должны быть прописаны соответствующие файлу параметры жирности и указан правильный путь до файла шрифта.
4. Подключить файл css\base\_fonts.scss в основной файл стилей проекта css\main.scss используя конструкцию @import
5. подключить файл normalize с официального сайта https://necolas.github.io/normalize.css/ на страницу проекта index.html. Учти, что файл должен быть локальным (нужно скачать в папку проекта), перед тем как подключать!
6. в стилевом файле css\base\_global.scss проставь все недостающие стили согласно макета и подключи в основной стилевой файл css\main.scss после шрифтов.
7. Подключи вспомогательный стилевой файл css\utils\_visually-hidden.scss в основной стилевой файл.

## Задание 2

1. Выполнить HTML-разметку следующих секций по BEM

          block__element--modifier

    секции которые нужно разметить:

    - first-screen
    - benefits
    - services
    - price

   все размеченные элементы секций должны иметь свои  css-классы согласно иерархии bem-блока.

2. Экспортировать векторные иконки из макета в папку svg. Все названия иконок должны начинаться с icon- Названия иконок должны описывать то что изображено на ней. Пример: иконка в виде копилки-хрюшки должна называться piggy-bank. Плохой пример: bank-in-the-shape-of-a-pig. Названия должны быть простыми и понятными, что бы ты могла ориентироваться по списку иконок в проводнике.

## Задание 3

1. в папке стилей css\blocks создай файл бэм блока button и пропиши соответствующие стили для этого элемента согласно макета. Затем подключи этот стилевой файл в основной стилевой файл css\main.scss в соответствующий комментариям раздел
2. Создай файл бэм блока title и по аналогии с кнопкой пропиши стили, подключи в основной стилевой файл.
3. в папке css\sections создай файлы для каждой смысловой секции, которую ты разметила и подключит в основной стилевой файл.


