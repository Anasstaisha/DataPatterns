[![Build status](https://ci.appveyor.com/api/projects/status/qsdvaivkkw50dxfi?svg=true)](https://ci.appveyor.com/project/Anasstaisha/datapatterns)


# Задача №1: заказ доставки карты (изменение даты)

Вам необходимо автоматизировать тестирование новой функции формы заказа доставки карты:

![image](https://github.com/netology-code/aqa-homeworks/raw/master/selenide/pic/order.png)

Требования к содержимому полей, сообщения и другие элементы, по словам заказчика и разработчиков, такие же, они ничего не меняли.

Тестируемая функциональность: если заполнить форму повторно теми же данными, за исключением «Даты встречи», то система предложит перепланировать время встречи:

![image](https://github.com/netology-code/aqa-homeworks/raw/master/patterns/pic/replan.png)

После нажатия кнопки «Перепланировать» произойдёт перепланирование встречи:

![image](https://github.com/netology-code/aqa-homeworks/raw/master/patterns/pic/success.png)

Важно: в этот раз вы не должны хардкодить данные прямо в тест. Используйте Faker, Lombok, data-классы для группировки нужных полей и утилитный класс-генератор данных.
