> 1.Создать репозиторий на GitHub   
2.Нарисовать блок-схему алгоритма   
> 3. Снабдить репозиторий оформленным текстовым описанием решения (файл  Readme.md)   
> 4. Написать программу, решающую поставленную задачу
5.Использовать контроль версий в работе над небольшим проектом( не должно быть так, что все залито одним коммитом, как минимум этапы 2,3, и 4 должны быть расположены в разных коммитах)
>> **Задача:**  Написать программу, которая из имеющегося массива строк формирует массив строк, длина которых меньше либо равна 3 символа. Первоначальные массив можно вывести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.   
> **Примеры:**  
[“hello”,”2”,”world”,”:-)”]->[“2”,”😊”]
[“1234”,”1567”,”-2”,”computer science”]->[“-2”]
[“Russia”,”Denmark”,”Kazan”]->[]




# Описание решения:
Показываем два массива: массив 1 и массив 2. 
Используем метод, в котором цикл соизмерим длине массива, с условием проверки цикла (<= 3), если "ДА" элемент массива 1 заносится в count элемента массива 2. Переменная сount увеличивается на 1 и возращается к циклу (for) в котором i увеличивается на 1. 
[блок-схема]<a href="https://ibb.co/chXLYbf"><img src="https://i.ibb.co/RT4yjhr/bloc-chema.png" alt="bloc-chema" border="0"></a>