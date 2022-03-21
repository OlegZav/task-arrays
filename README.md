# Arrays

Установите зависимости:

```
npm install
```

В файле `src/Arrays.js` Создайте функции `arraySorting()`, `arrayFiltering()` и `arrayPushing()`, реализующие следующий функционал:

1. В функцию `arraySorting()` приходит строка чисел с разделительными запятыми вида `"1,2,33,0,17"`.
   Преобразуйте строку в массив чисел, отсортируйте их по возрастанию и верните строку с упорядоченными числами, разделенными запятыми.

2. В функцию `arrayFiltering()` приходит массив целых чисел.
   Преобразуйте массив таким образом, чтобы все элементы массива, в которых содержатся числа более `100`, были бы удалены из массива, и верните его в качестве результата функции.

3. В функцию `arrayPushing()` приходят два массива целых чисел размерностью `5` элементов.
   Получите третий массив размерностью `10` элементов, в котором последовательно чередуются значения из первых двух массивов, и верните его в качестве результата функции.

Проверить себя можно запустив команду `npm run test`.

После выполнения задания создайте pull request с решением.
