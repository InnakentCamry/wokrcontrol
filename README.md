# Итоговая проверочная работа
1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный метод)
3. Снабдить репозиторий оформленный текствовым описанием решения (файл README.MD)
4. Написать программу, решаюущую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что все залито одним коммитом, как минимум этапы 2, 3, 4 должны быть расположены в разныхи коммитах)
![Диаграмма](https://user-images.githubusercontent.com/115144084/199673019-f9736ec3-6791-4254-a7e8-5b78b5c287fc.png)
# **Задача**
Написать программу, которая из имеющегося массива строк формирует массив строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
# Примеры
["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> [" "]
# Алгоритм решения:
1. Делаем перебор значений из исходного массива
2. Проверяем каждое значение из массива на соответствие условию: длина строки меньше или равна трем
3. Если строка удовлетворяет условию кладем значение в новый массив
4. Повторяем пункты 2 и 3 до тех пор пока не достигнем конца исходного массива
5. Возвращаем новый заполненый массив как результат
# Программа:
> Для запуска программы перейдите в файл Program.cs и запустите команду через терминал:

dotnet run 
Далее введите значения через пробел, например:

Введите значения через пробел: 2 hello sun 33 world
Пример вывода программы:

[2, hello, sun, 33, world] -> [2, sun, 33]
