Задание на экзамен (пиццерия)
===========
Написать программу, которая состоит из следующих частей:<br>
1. Окно ввода параметров пиццерии (название и количество курьеров). Дефолтное название - “пицца вкусная”, количество курьеров - 3. Показывается только при первом запуске приложения.<br>
2. Список заказов, отсортированный по времени выхода курьера (3 колонки: название пиццы, номер курьера и время начала доставки).<br>
3. Окно добавления заказа (название пиццы, номер телефона, адрес, предполагаемая "скорость" доставки (от 30 минут до 1:30 с градацией по полчаса) и выбор времени доставки комбобоксом), открывается по клику на кнопку "добавить"/"+". Комбобокс с выбором времени показывает только свободное время, становится активным после выбора "скорости" доставки.<br>
4. Окно с подробностями заказа (+номер телефона, адрес и "скорость" доставки), окрывается по клику на заказ. В этом окне данные редактировать нельзя.<br>
5. Окно редактирования времени, открывается из контекстного меню по длинному клику на заказ. В том же меню должно быть и удаление заказа (с подтверждением).<br>
6. Заказы распределяются по курьерам автоматически.

Режим работы пиццерии с 10:00 до 24:00.

Все данные должны храниться в sqlite базе данных.

Система оценок:
- Программа, в которой реализованы пункты 1-3: 10 балла
- Пункт 4 и 6: 5 балла
- Пункт 5: 5 балла
- Дополнительные баллы могут быть поставлены за хороший код и красивый дизайн.
- Итоговая оценка может быть снижена за плохой код/дизайн (например, список, элементы которого не кликаются по всей ширине и многострочный EditText).
 
Суммарный балл может быть снижен за плохой код, так то русский в коде/комментариях, незакрытые ресурсы, строчки в коде вместо strings.xml, wrap_content для ListView итд, равно как и плохой кастомный дизайн.

Ничего из указанного выше не отменяет здравый смысл.

Задание необходимо сдавать в виде пулл-реквеста (код+apk) к https://github.com/IFMO-MobDev-2013/exam2 до 17:30 21.01.14.
