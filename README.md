# Курсовая работа ИА-132
#### тема:
Поиск палиндромов в тексте  
Задание  
Разработать программу palindrom, выполняющую поиск всех палиндромов в заданном тексте. Команда palindrom принимает в качестве аргумента командной строки имя файла, содержащего текст на русском языке. Все найденные палиндромы распечатываются на экране.  
Критерии оценки  
Оценка «удовлетворительно»: реализована проверка того, что весь текст входного файла целиком является палиндромом. Не предусмотрено динамическое выделение памяти под входные данные.  
Оценка «хорошо»: реализована предварительная обработка текста: из каждого предложения удаляются все знаки препинания. После этого осуществляется проверка каждого предложения на выполнение свойства палиндрома. Обязательно динамическое выделение памяти под входные данные.  
Оценка «отлично»: реализована предварительная обработка текста: из текста удаляются все пробелы и знаки препинания так, чтобы получилось одно большое слово. Для поиска подпалиндромов используется алгоритм, основанный     на     применении     динамического     программирования  (http://comp-science.narod.ru/WebPage/p6.html). Обязательно динамическое выделение памяти под входные данные.  
 
Указания к выполнению задания  
Палиндромом называются слово (потоп, шалаш) или текст (а роза упала на лапу Азора), читающиеся одинаково в обоих направлениях.  
Запуск программы должен производиться со следующими аргументами командной строки:  

Программа выполняет поиск всех палиндромов в файле text.txt и распечатывает результат работы на экране.  