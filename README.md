# Домашнее задание к занятию "`Работа с данными (DDL/DML)`" - `Никулин Михаил Сергеевич`



---

### Задание 1

`Создаем базу, создаем пользователя`

![create_user.png](img%2Fcreate_user.png)

`Добавляем привилегии`

![grand_all_privileges_to_sys_temp.png](img%2Fgrand_all_privileges_to_sys_temp.png)
![privileges.png](img%2Fprivileges.png)

`Подключаемся под sys_temp`

![reconnect_to_db_sys_temp.png](img%2Freconnect_to_db_sys_temp.png)

`Создаем пустую базу sakila, восстанавливаем из дампа, строим диаграмму`

![er.png](img%2Fer.png)


---

### Задание 2

```
Название таблицы           | Название первичного ключа
customer                   | customer_id
rental                     | rental_id
payment                    | payment_id
inventory                  | inventory_id
store                      | store_id
staff                      | staff_id
address                    | address_id
city                       | city_id
country                    | country_id
film                       | film_id
language                   | language_id
film_actor                 | actor_id
                           | film_id
actor                      | actor_id
film_category              | film_id
                           | category_id
category                   | category_id
staff_list                 |
customer_list              | 
nicer_but_slower_film_list |
sales_by_film_category     |
film_text                  | film_id
sales_by_store             |
actor_info                 |
film_list                  |
```


---


## Дополнительные задания (со звездочкой*)


### Задание 3*

`Убираем права на добавление, удаление, изменение`

![revoke_privilages.png](img%2Frevoke_privilages.png)
![revoke_privilages_2.png](img%2Frevoke_privilages_2.png)
![revoke_privilages_3.png](img%2Frevoke_privilages_3.png)
