[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/NoA0nk0P)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12715867&assignment_repo_type=AssignmentRepo)
<h1>База данных cooking_bd</h1><br>
<h3>Структура таблицы bookmark</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
user_id	int	Нет	<br>
recipe_id	int	Нет	<br>
<h3>Дамп данных таблицы bookmark</h3><br>
<br>
<h3>Структура таблицы category</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
title	varchar(255)	Нет	<br>
<h3>Дамп данных таблицы category</h3><br>
1	<br>
2	Первые блюда<br>
3	Вторые блюда<br>
4	Закуски<br>
5	Салаты<br>
6	Соусы<br>
7	Кремы<br>
8	Напитки<br>
9	Десерты<br>
10	Выпечка<br>
11	Торты<br>
12	Хлеб<br>
13	Блины<br>
<h3>Структура таблицы comment</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
user_id	int	Нет	<br>
recipe_id	int	Нет	<br>
text	varchar(255)	Нет	<br>
data	datetime	Нет	<br>
<h3>Дамп данных таблицы comment</h3><br>
<br>
<h3>Структура таблицы compound</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
recipe_id	int	Нет	<br>
product_id	int	Нет	<br>
quantity	int	Нет	<br>
<h3>Дамп данных таблицы compound</h3><br>
<br>
<h3>Структура таблицы cooking_method</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
recipe_id	int	Нет	<br>
description	varchar(255)	Да	NULL<br>
video	varchar(255)	Да	NULL<br>
<h3>Дамп данных таблицы cooking_method</h3><br>
<br>
<h3>Структура таблицы images</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
recipe_id	int	Нет	<br>
image	varchar(255)	Да	NULL<br>
<h3>Дамп данных таблицы images</h3><br>
<br>
<h3>Структура таблицы ingredient</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
title	int	Нет	<br>
quantity_ingredients	int	Нет	<br>
<h3>Дамп данных таблицы ingredient</h3><br>

<h3>Структура таблицы kitchen</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
title	varchar(255)	Нет	<br>
<h3>Дамп данных таблицы kitchen</h3><br>
1	Итальянская<br>
2	Грузинская<br>
3	Китайская<br>
4	Французская<br>
5	Русская<br>
6	Японская<br>
7	Индийская<br>
8	Мексиканская<br>
<h3>Структура таблицы like</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
user_id	int	Нет	<br>
recipe_id	int	Нет	<br>
<h3>Дамп данных таблицы like</h3><br>
<br>
<h3>Структура таблицы menu</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
title	varchar(255)	Нет	<br>
<h3>Дамп данных таблицы menu</h3><br>
1	Безглютеновая диета<br>
2	Вегетарианская еда<br>
3	Веганская еда<br>
4	Безлактозная еда<br>
5	Детское меню<br>
6	Низкокалорийная еда<br>
7	Постная еда<br>
8	Меню при диабете<br>
<h3>Структура таблицы product</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
title	varchar(255)	Нет	<br>
unit_id	int	Нет	<br>
<h3>Дамп данных таблицы product</h3><br>
<br>
<h3>Структура таблицы rating_recipe</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
recipe_id	int	Нет	<br>
week_start	date	Нет	<br>
week_end	date	Нет	<br>
rating	decimal(10,0)	Нет	<br>
<h3>Дамп данных таблицы rating_recipe</h3><br>
<br>
<h3>Структура таблицы rating_user</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
user_id	int	Нет	<br>
week_start	date	Нет	<br>
week_end	date	Нет	<br>
rating	decimal(10,0)	Нет	<br>
<h3>Дамп данных таблицы rating_user</h3><br>
<br>
<h3>Структура таблицы recipe</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
user_id	int	Нет	<br>
category_id	int	Нет	<br>
kitchen_id	int	Нет	<br>
menu_id	int	Нет	<br>
title	varchar(255)	Нет	<br>
quantity_ingredients	int	Да	NULL<br>
portion	int	Нет	<br>
cooking_time	time	Нет	<br>
<h3>Дамп данных таблицы recipe</h3><br>
1	1	8	5	5	Лимонад	NULL	1	00:22:05<br>
<h3>Структура таблицы unit</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
title	varchar(255)	Нет	<br>
<h3>Дамп данных таблицы unit</h3><br>
<br>
<h3>Структура таблицы user</h3><br>
<h5>Столбец	Тип	Null	По умолчанию</h5><br>
id	int	Нет	<br>
name	varchar(255)	Нет	<br>
surname	varchar(255)	Нет	<br>
email	varchar(255)	Нет	<br>
password	varchar(255)	Нет	<br>
number_subscribers	int	Да	0<br>
number_subscriptions	int	Да	0<br>
rating	int	Да	0<br>
image	text	Да	NULL<br>
<h3>Дамп данных таблицы user</h3><br>
1	Александра	Чугаенко	s@mail.ru	123	0	0	0	NULL<br>
2	Варвара	Григорьева	v@mail.ru	123	0	0	0	NULL<br>
3	Ника	Подовалова	n@mail.ru	123	0	0	0	NULL<br>


