[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/NoA0nk0P)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12715867&assignment_repo_type=AssignmentRepo)
<h1>База данных cooking_bd</h1>
Структура таблицы bookmark
Столбец	Тип	Null	По умолчанию
id	int	Нет	
user_id	int	Нет	
recipe_id	int	Нет	
Дамп данных таблицы bookmark

Структура таблицы category
Столбец	Тип	Null	По умолчанию
id	int	Нет	
title	varchar(255)	Нет	
Дамп данных таблицы category
1	
2	Первые блюда
3	Вторые блюда
4	Закуски
5	Салаты
6	Соусы
7	Кремы
8	Напитки
9	Десерты
10	Выпечка
11	Торты
12	Хлеб
13	Блины
Структура таблицы comment
Столбец	Тип	Null	По умолчанию
id	int	Нет	
user_id	int	Нет	
recipe_id	int	Нет	
text	varchar(255)	Нет	
data	datetime	Нет	
Дамп данных таблицы comment

Структура таблицы compound
Столбец	Тип	Null	По умолчанию
id	int	Нет	
recipe_id	int	Нет	
product_id	int	Нет	
quantity	int	Нет	
Дамп данных таблицы compound

Структура таблицы cooking_method
Столбец	Тип	Null	По умолчанию
id	int	Нет	
recipe_id	int	Нет	
description	varchar(255)	Да	NULL
video	varchar(255)	Да	NULL
Дамп данных таблицы cooking_method

Структура таблицы images
Столбец	Тип	Null	По умолчанию
id	int	Нет	
recipe_id	int	Нет	
image	varchar(255)	Да	NULL
Дамп данных таблицы images

Структура таблицы ingredient
Столбец	Тип	Null	По умолчанию
id	int	Нет	
title	int	Нет	
quantity_ingredients	int	Нет	
Дамп данных таблицы ingredient

Структура таблицы kitchen
Столбец	Тип	Null	По умолчанию
id	int	Нет	
title	varchar(255)	Нет	
Дамп данных таблицы kitchen
1	Итальянская
2	Грузинская
3	Китайская
4	Французская
5	Русская
6	Японская
7	Индийская
8	Мексиканская
Структура таблицы like
Столбец	Тип	Null	По умолчанию
id	int	Нет	
user_id	int	Нет	
recipe_id	int	Нет	
Дамп данных таблицы like

Структура таблицы menu
Столбец	Тип	Null	По умолчанию
id	int	Нет	
title	varchar(255)	Нет	
Дамп данных таблицы menu
1	Безглютеновая диета
2	Вегетарианская еда
3	Веганская еда
4	Безлактозная еда
5	Детское меню
6	Низкокалорийная еда
7	Постная еда
8	Меню при диабете
Структура таблицы product
Столбец	Тип	Null	По умолчанию
id	int	Нет	
title	varchar(255)	Нет	
unit_id	int	Нет	
Дамп данных таблицы product

Структура таблицы rating_recipe
Столбец	Тип	Null	По умолчанию
id	int	Нет	
recipe_id	int	Нет	
week_start	date	Нет	
week_end	date	Нет	
rating	decimal(10,0)	Нет	
Дамп данных таблицы rating_recipe

Структура таблицы rating_user
Столбец	Тип	Null	По умолчанию
id	int	Нет	
user_id	int	Нет	
week_start	date	Нет	
week_end	date	Нет	
rating	decimal(10,0)	Нет	
Дамп данных таблицы rating_user

Структура таблицы recipe
Столбец	Тип	Null	По умолчанию
id	int	Нет	
user_id	int	Нет	
category_id	int	Нет	
kitchen_id	int	Нет	
menu_id	int	Нет	
title	varchar(255)	Нет	
quantity_ingredients	int	Да	NULL
portion	int	Нет	
cooking_time	time	Нет	
Дамп данных таблицы recipe
1	1	8	5	5	Лимонад	NULL	1	00:22:05
Структура таблицы unit
Столбец	Тип	Null	По умолчанию
id	int	Нет	
title	varchar(255)	Нет	
Дамп данных таблицы unit

Структура таблицы user
Столбец	Тип	Null	По умолчанию
id	int	Нет	
name	varchar(255)	Нет	
surname	varchar(255)	Нет	
email	varchar(255)	Нет	
password	varchar(255)	Нет	
number_subscribers	int	Да	0
number_subscriptions	int	Да	0
rating	int	Да	0
image	text	Да	NULL
Дамп данных таблицы user
1	Александра	Чугаенко	s@mail.ru	123	0	0	0	NULL
2	Варвара	Григорьева	v@mail.ru	123	0	0	0	NULL
3	Ника	Подовалова	n@mail.ru	123	0	0	0	NULL


