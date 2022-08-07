## Исходные данные
Массив пользователей  

    $users = [
        [
            'id' => 1,
            'name' => 'Alexander Petrov',
            'email' => 'alex777@mail.ru',
        ],
        [
            'id' => 2,
            'name' => 'Igor Matveev',
            'email' => 'igoryan1989@mail.ru',
        ],
        [
            'id' => 3,
            'name' => 'Polina Chizhova',
            'email' => 'polyachizh@yandex.ru',
        ],
        [
            'id' => 4,
            'name' => 'Alexander Ignatyev',
            'email' => 'ignatyev.a@gmail.com',
        ],
        [
            'id' => 5,
            'name' => 'Oksana Sirenevaya',
        ],
    ];

## Задания
1) Вывести все пары И+Ф в одной строке, разделив их запятой и пробелом.  
Результат:  
   `Alexander Petrov, Igor Matveev, Polina Chizhova, Alexander Ignatyev, Oksana Sirenevaya`
   <br><br>
2) Найти пользователя с именем Polina. Вывести name и email в виде строки через запятую.
   Если поле email не задано, то вывести только name.
Результат:  
`Polina Chizhova, polyachizh@yandex.ru`
<br><br>
3) Составить список id пользователей, у которых заполнен email. Вывести в виде массива.  
Результат:  

       $idList = [
           1,
           2,
           3,
           4,
       ];
4) Получить последнего пользователя из массива. Вывести name и email в виде строки через запятую.  
Если поле email не задано, то вывести только name.  
Результат:  
`Oksana Sirenevaya`  
<br>
5) Получить список используемых пользователями почтовых сервисов. Сервисы не должны повторяться. 
Результат вывести в виде массива строк.  
Результат:  

       $services = [
          'mail.ru',
          'yandex.ru',
          'gmail.com',
       ];
6) Сгруппировать пользователей по используемому почтовому сервису. Результат вывести в виде массива
с названиями сервисов в ключах и массивами id в значениях.  
Результат:  

       $services = [
           'mail.ru' => [
               1,
               2,
           ],
           'yandex.ru' => [
               3,
           ],
           'gmail.com' => [
               4,
           ],
       ];
7) Определить почтовый сервис, наиболее популярный среди пользователей. Вывести в виде строки.  
Результат:  
`mail.ru`