# Кофемашина
Программа является REST-кофеваркой, которая имеет следующие функции:
- Показывает список имеющихся в её резервуарах ингредиентов для кофе;
- Позволяет пополнить резервуар с тем или иным ингредиентом;
- Отсеивает лишнее, если в кофемашину положили слишком много ингредиентов;
- Показывает список кофе, которые умеет делать кофемашина;
- Готовит кофе по вашему выбору из имеющихся ингредиентов :)
- В случае нехватки ингредиентов, уведомляет пользователя о том, каких именно ингредиентов не хватает.

База данных кофемашины состоит из следующих таблиц:
- Виды кофейных напитков:
  * Id
  * Id рецепта для приготовления эспрессо
  * Количество дополнительной воды
  * Название напитка
- Рецепты эспрессо:
  * Id
  * Количество воды
  * Количество кофе
- Молоко:
  * Id
  * Количество молока
  * Взбитость молока
- Вид кофе _ Молоко (соединительная таблица):
  * Id кофейных напитков
  * Id молока
- Ингредиенты:
  * Id
  * Название
  * Количество, содержащееся на данный момент в резервуаре
  
 В работе использовались:
 - Java
 - PostgreSQL
 - Spring Boot
 - Swagger
