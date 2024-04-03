# Позиционирование
## Абсолютное позиционирование - элемент перемещяется по браузеру, если его никто не ограничивает (относительное позиционирование родителя)... блок подпрыгивает и его место занимают соседние элементы
## Относительное позиционирование - при смещении блока соседние элементы "думают" что блок не перемещался
## Фиксированое позиционирование - всегда перемещается по браузеру 
## Прилипающее позиционирование - ОБЯЗАТЕЛЬНО нужно указывать смещение
## По умолчанию все блоки имеют позицию: static
## z-index: работает только в спозициониравоных блоках
## Задание - создать в центре экрана карточку товара :D (размер экрана не известен) 
Задали карточке фиксированный размер по высоте и ширине + воспользовались свойством overflow со значением after для формирования скролла если контент не поместится внутри карточки...
Сама карточка абсолютно спозиционирована 50% от верха и 50% от левого края + выполнено смещение на -50% от ширины и высоты самой карточки transform: translate(-50%, -50%);
Познакомились с генеротароми изображений (смотри интеллект карту https://goo.su/front)
Сформировали кнопку из тега 'a' - добавили в кнопкуЖ
-- display: inline-block;
-- border: 2px solid gray;
-- text-transform: uppercase;
-- letter-spacing: 5px;
-- border-radius: 10px;
-- transition: 0.8s;
-- воспользовались свойством hover (свойства при наведении курсора мышки на блок)
-- ограничили проект одним экраном html{height: 100%} и body{heigh: 100%}
