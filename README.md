Написать программу, которая из массива строк формирует массив из строк, длинна которых меньше или равна 3 символа.

1. Сдаем ручное поэлементное заполнение массива через терминал
   * запрос на количество элементов в массиве
   * заполняем каждый индекс массива 
2. Пишем метод выполняющий условие задачи
   * создаем Счетчик
   * создаем Новый массив равный длине Принятого
   * создаем цикл, в котором проверяем элементы из Принятого массива на условие задачи. Если условие соблюдается, то записываем этот элемент в Новый массив с индексом счетчика. В конце Нового массива могу образоваться индексы со значением NULL
   * создаем Итоговый массив равный значению Счетчика
   * через цикл переписывает из Нового массива элементы в Итоговый массив
   * выводим Итоговый массив
3. Пишем метод вывода массива в терминал. Каждый элемент отделяем запятой
    * через цикл выводим каждый элемент с проверкой
      * если элемент не последний, то выводим с запятой
      * иначе без запятой
  
