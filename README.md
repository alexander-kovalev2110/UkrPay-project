# UkrPay-project
Задача:

	Реализовать простое приложение в котором будет 3 части:

Таблица посылок - содержит такие колонки ( 1. Номер ( number ) 2. Статус ( status ) 3. Местоположение ( location ) 4. Количество ( count) ), которые взяты из следующего массива

[
 { number: ‘0001’, status : ‘in process’, location: ‘Kyiv’, count: 5  },
 { number: ‘0002’, status : ‘success’, location: ‘Vinnystya’, count: 7  },
 { number: ‘0003’, status : ‘failed’, location: ‘Odessa’, count: 1  },  
 { number: ‘0004’, status : ‘success’, location: ‘Kharkiv’, count: 15  }, 
 { number: ‘0005’, status : ‘success’, location: ‘Odessa’, count: 15  }, 
 { number: ‘0006’, status : ‘failed’, location: ‘Lviv’, count: 2  },  
]


Действия с посылками - создать / удалить. 

Создание должно происходить с выше перечисленными характеристиками. 

number - непустая строка с длинной не более 10 символов.
status - один из трех на выбор ( in process, success, failed ) в select-е.
location - непустая строка с длинной не более 30 символов.
count - натуральное число не превышающее 100.

Кнопка удаления срабатывает только при выборе записи в таблице.

Фильтрация в таблице. Сделать возможность фильтровать таблицу по колонке number и status, вводя данные в форму фильтрации в input и select соответственно. Запускать фильтрацию при нажатии на кнопку “Фильтровать”. 
