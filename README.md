# additional-storage-ocmod [![GitHub version](https://badge.fury.io/gh/dtaipov%2Fadditional-storage-ocmod.svg)](https://badge.fury.io/gh/dtaipov%2Fadditional-storage-ocmod)
Позволяет вводить количество товара на втором складе в администраторской части и видеть это количество на странице карточки товара и на странице Закладки.

Изменения в Администраторской части:  
Форма редактирования товара. Закладка Данные  
Новое поле "Количество Склад2" под полем "Количество"  

Изменения в интерфейсе пользователя:  
1) Карточка товара. Теперь тут два количества - "Наличие НГР" и "Наличие ДРЖ"  
2) Закладки. Новое поле "Наличие Дирижабельная" в таблице.  

Установка.
Меню "Установка расширений", загрузить файл additional-storage-ocmod.ocmod.zip  
Меню "Модификаторы" - список установленных расширений  
Нажать кнопку "Обновить" в верхнем правом углу  

Удаление.
Меню "Модификаторы" - выделить расширение "Additional storage", нажать кнопку Удалить в верхнем правом углу, нажать кнопку "Обновить" в верхнем правом углу.  

Известные недоработки:  
1) При заказе товара проверяется наличие только на первом складе.  
Вычитание со склада происходит только на первом складе.  
2) Надпись в случае отсутствия товара на втором складе фиксирована и равна "В наличии".  
Тогда как эту надпись можно менять при редактировании товара для первого склада (поле "Отсутствие на складе").  

### Get Started

  * [Read the documentation](https://github.com/dtaipov/additional-storage-ocmod/wiki).
  
