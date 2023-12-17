# RGR
Репозиторий для телеграм-бота по спс
# Расчётно-графическая работа. "Управление складом: Эффективность и Оптимизация"
Целью данного проекта является создание системы управления складскими процессами с использованием современных технологий и методов. Основной фокус направлен на повышение эффективности, оптимизацию ресурсов и улучшение общей производительности складского хозяйства.
Основные характеристики:
Автоматизация процессов: Внедрение современных систем автоматизации, таких как использования телеграм-ботов, для более простого пути получения информации о товарах.
Чтобы запустить проект на локальной машине, необходимо:
1. Создать два проекта python, в один из которых нужно вставить код дашбордов, а в другой код тг бота. Проект с ботом необходимо назвать "pythonProject7", чтобы не изменять код. Также в проект с ботом необходимо добавить csv файл с названием "TextFile1.csv".
2. Необходимо запустить оба файла в программе "PyCharm Community Edition".
3. Далее можно пользоваться ботом, а при открытии страницы с дашбордами желательно обновлять её каждый раз.

#
При работе с ботом необходимо соблюдать особый синтаксис, который существенно упростил написание кода и его читаемость:
1. При добавлении товара на склад необходимо использовать команду /add с уже указанными атрибутами товара на английском языке. То есть необходимо писать «/add Название товара, Описание товара, Цена, Количество на складе, Количество проданных». Пример:
«/add Desk, Furniture, 10000, 5, 20».
2. При обновлении товара необходимо полностью написать все атрибуты товара, изменив нужное поле. Пример:
«/update Desk, Furniture, 15000, 5, 35».
3. При удалении товара необходимо написать название товара, который нужно удалить. Пример: 
«/delete Desk».
4. Если необходимо увидеть список товаров на складе, нужно написать «/list».
 
