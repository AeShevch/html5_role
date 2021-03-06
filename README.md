# HTML5 role аттрибут.

## Основные и наиболее часто используемые значения role
* **banner** - содержит главный заголовок или внутренний заголовок страницы. Например логотип и название сайта. Рекомендуется использовать не больше одного раза на странице.
* **complementary** - информационный блок, отделенный от основного содержания ресурса.
* **contentinfo** - обобщающая информация о содержании страницы ( к примеру футер сайта ). Рекомендуется использовать не больше одного раза на странице.
* **definition** - указывает определение термина или понятия.
* **main** - выступает в качестве основного содержания документа. Рекомендуется использовать не больше одного раза на странице.
* **navigation** - набор элементов предназначенных для навигации по документу или связанным документам. Рекомендуется использовать не больше одного раза на странице.
* **note** - заметка ( вспомогательная информация) к основному содержанию ресурса.
* **search** - указывает область для поиска по содержимому.

### Упрощенный пример использования

```<a href="/" role="banner"><img src="logo.png" alt="" />Блог Васи Пупкина</a>```
 
```
<nav role="navigation">
	<ul>
		<li><a href="/">Главная</a></li>
		<li><a href="/news">Новости</a></li>
		<li><a href="/contacts">Контакты</a></li>
	</ul>
</nav>
```
```
 <main role="main">
    <h1>Я, Вася Пупкин</h1>
    <p>Привет мир!</p>
    <p>Очень хочу чтобы вы поделились со мной мыслями по этому поводу.</p>
    <p role="definition">* полномочиями не стоит злоупотреблять</p>
    <p role="note">** работаем с 2011 года.</p>
</main>
```
```
<aside role="complementary">
		<b>Выбери любимое животное</b>
		<ul>
			<li><a href="#">Медведь</a></li>
			<li><a href="#">Дельфин</a></li>
			<li><a href="#">Носорог</a></li>
		</ul>
</aside>
```
```
<aside role="search">
<form>
Поиск по товару: <input type="text" /> <input type="submit" value="Найти" />
</form>
</aside>
```
```
<div role="contentinfo">
	<p>© 2012 Сайт разработан Васей Пупкиным.</p>
</div>
 ```

## Возможные значения role

В следующей таблице приведены другие возможные значения атрибута role:

| Значение | Назначение |
| -------- | ---------- |
| alert	| Сообщение с важной и, как правило срочной, информация. Также см. *alertdialog* и *status*. |
| alertdialog	| Сообщение, которое содержит важную информацию, и первоначальный акцент переходит элементу в диалоговом окне. Также см. *alert* и *dialog*. |
| application	| Область объявленная как веб-приложение, в отличие от веб-документа. |
| article	| Раздел состоящий из композиции, которая в свою очередь образует самостоятельную часть документа, страницы или сайта. |
| button	| Кнопка, позволяющая пользователю вызвать какие-либо действия. Также см. *link*. |
| checkbox	| Чекбокс, который имеет три возможных значения: истина, ложь, или смешанное. |
| columnheader	| Ячейка таблицы, содержащая заголовок для столбца. |
| combobox	| Вариация селекта; аналогично textbox, позволяющая пользователям печатать для выбора опции, или при печате добавить новую опцию к списку. Также см. *listbox*. |
| dialog	| Сообщение, предназначенное для прерывания обработки текующего приложения, для ввода пользователем какой-либо информации или требующее от него какое-либо действие. Также см. *alertdialog*. |
| directory	| Список ссылок на части группы, например содержание. |
| document	| Область, содержащая информацию, которая объявлена как содержимое документа, в отличие от веб-приложений. |
| form	| Ориентир области, которая содержит коллекцию элементов и объектов, которые, в целом, объединяются, чтобы создать форму. См. также *search*. |
| grid	| Сетка интерактивного управления, которая содержит элементы сведенные в таблицу данных, в виде строк и столбцов, как таблица. |
| gridcell	| Ячейки в сетке или древовидная сетка. |
| group	| Набор объектов пользовательского интерфейса, которые не предназначены для включения в итоговую страницу или содержимое, вспомогательных технологий. |
| heading	| Заголовок для раздела страницы. |
| img	| Контейнер для набора элементов, которые формируют изображение. |
| link	| Интерактивная ссылка на внутренний или внешний ресурс, который при активации заставляет браузер пользователя перейти к этому ресурсу. См. также *button*. |
| link	| Интерактивная ссылка на внутренний или внешний ресурс, который при активации приводит к переходу браузера пользователя к этому ресурсу. См. также *button*. |
| list	| Группа неинтерактивных элементов списка. Также см. *listbox*. |
| listbox	| Виджет, который позволяет пользователю выбрать один или несколько элементов из списка вариантов. См. также *combobox* и *list*. |
| listitem	| Один элемент в списоке или содержании. |
| log	| Тип интерактивной области, где новая информация добавляется в осмысленном порядке, а старая может исчезнуть. См. также *marquee*. |
| marquee	| Тип интерактивной области, где не существенная информация часто меняется. См. также *log*. |
| math	| Контент, который представляет собой математическое выражение. |
| menu	| Тип виджета, который предоставляет выбор списка вариантов для пользователя. |
| menubar	| Представление menu, которое обычно остается видимым и, как правило, представлено горизонтально. |
| menuitem	| Опции в группе выбора содержащиеся в menu или menubar. |
| menuitemcheckbox	| Чекбокс пункта menu, который имеет три возможных значения: истина, ложь, или смешанное. |
| menuitemradio	| Отмечаемый пункт меню в группе menuitemradio, из которых только один может быть выбран одновременно. |
| option	| Выбираемый элемент в списке выбора. |
| presentation	| Элемент чья семантически неявная роль не будет отображаться на доступности API. |
| progressbar	| Элемент, который отображает ход статуса задач, занимающих много времени. |
| radio	| Отмечаемый пункт в группе таких же пунктов, из которых только один может быть выбран одновременно. |
| radiogroup	| Группа переключателей. |
| region	| Большая область веб-страницы или документа, которую автор счел достаточно важной, чтобы включить в основную информацию страницы или оглавление, например, область страницы содержающая спортивную статистику событий онлайн. |
| row	| Ряд ячеек в grid. |
| rowgroup	| Группы, содержащие один или несколько элементов row в grid. |
| rowheader	| Ячейка содержащая заголовок для row в grid. |
| scrollbar	| Графический объект, который управляет прокруткой содержимого области просмотра, независимо от того, полностью ли содержание отображается в области просмотра. |
| separator	| Разделитель, который разделяет и отличает разделы содержимого или группы пунктов menuitems. |
| slider	| Интерфейс ввода для пользователя, когда пользователь выбирает значение из заданного диапазона. |
| spinbutton	| Форма диапазона, где пользователь может выбрать из числа дискретных решений. |
| status	| Контейнер, содержание которого носит рекомендательный характер для информирования пользователя, но не является достаточно важным. Также см. *alert*. |
| tab	| Вкладка, представляющая из себя механизм для выбора вкладки необходимой пользователю. |
| tablist	| Список элементов tab, которые являются ссылками на tabpanel элементы. |
| tabpanel	| Контейнер для ресурсов связанных с tab, где каждый tab содержиться в tablist. |
| textbox	| Поле ввода, которое предоставляет ввод в свободной форме текста. |
| timer	| Тип интерактивной области, содержащую числовой счетчик, который указывает на количество затраченного времени от начальной точки, или время, оставшееся до конечной точки. |
| toolbar	| Набор часто используемых функциональных кнопок, представленых в компактной визуальной форме. |
| tooltip	| Контекстное всплывающее окно, которое отображает описание элемента. |
| tree	| Тип списка, который может содержать подуровни вложенных групп, которые могут быть свернуты и расширены. |
| treegrid	| Сетка, чьи строки могут быть свернуты и расширины так же как и в *tree*. |
| treeitem	| Опция элемента tree. Этот элемент внутри tree, может быть свернут или расширен, если имеет вложенный подуровень. |
