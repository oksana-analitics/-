Вы — аналитик данных. Руководитель дал вам задание поработать с таблицей logs действий пользователей (user_id, event, event_time, value). Действия пользователей поделены на сессии - последовательности событий, в которых между соседними по времени событиями промежуток не более 5 минут. Т.е. длина всей сессии может быть гораздо больше 5 минут, но между каждыми последовательными событиями не должно быть более 5 минут.
Поле event может принимать разные значения, в том числе ’template_selected’ (пользователь выбрал некий шаблон). В случае, если event=’template_selected’, то в value записано название этого шаблона (например, ’pop_art_style’).

Задача
Напишите SQL-запрос, выводящий 5 шаблонов, которые чаще всего применяются юзерами 2 и более раза подряд в течение одной сессии.# -
Проекты по направлению Аналитик данных
