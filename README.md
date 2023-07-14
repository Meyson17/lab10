
<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №10 <br>
по курсу «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"Java Script"</b><p>
<p align="right"><b>Выполнил: </b> студент 231 группы Рыжков Владимир</p>
<p  align="right"><b>Принял: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2023</p>
<h2> Введение </h2>
<p>Лабораторные работы по дисциплине «Web-технологии, языки и средства создания web-приложений» предназначены для освоения полученных теоретических знаний на практике. Цель работы - выполнить задачи, написав решение на Java Script:  <br>
<ol>
   <li>Напишите функцию, которая найдёт числа в массиве, которые делятся на заданное число​.
   <li>Нужно написать функцию, которая проверяет, являются ли две строки анаграммами, причем регистр букв не имеет значения. Учитываются лишь символы; пробелы или знаки препинания в расчет не берутся.
     <li>Нужно написать функцию, принимающую строку в качестве аргумента и возвращающую количество гласных, которые содержатся в строке.
Гласными являются «a», «e», «i», «o», «u».
       <li>Треугольник. Напишите цикл,  выводит такой треугольник:
         <li>FizzBuzz. Напишите программу, которая выводит через console.log все числа от 1 до 100, с двумя исключениями. Для чисел, нацело делящихся на 3, она должна выводить ‘Fizz’, а для чисел, делящихся на 5 (но не на 3) – ‘Buzz’.Когда сумеете – исправьте её так, чтобы она выводила «FizzBuzz» для всех чисел, которые делятся и на 3 и на 5.
           <li>Шахматная доска. Напишите программу, создающую строку, содержащую решётку 8х8, в которой линии разделяются символами новой строки. На каждой позиции либо пробел, либо #. 
             <li>Минимум. Напишите функцию min, принимающую два аргумента, и возвращающую минимальный из них.
               <li>Рекурсия. Ноль чётный. Единица нечётная. У любого числа N чётность такая же, как у N-2. Напишите рекурсивную функцию isEven согласно этим правилам. Она должна принимать число и возвращать булевское значение. Потестируйте её на 50 и 75. Попробуйте задать ей -1. Почему она ведёт себя таким образом? Можно ли её как-то исправить?
                 <li>Считаем бобы. Символ номер N строки можно получить, добавив к ней .charAt(N) ( “строчка”.charAt(5) ) – схожим образом с получением длины строки при помощи .length. Возвращаемое значение будет строковым, состоящим из одного символа (к примеру, “к”). У первого символа строки позиция 0, что означает, что у последнего символа позиция будет string.length – 1. Другими словами, у строки из двух символов длина 2, а позиции её символов будут 0 и 1.Напишите функцию countBs, которая принимает строку в качестве аргумента, и возвращает количество символов “B”, содержащихся в строке.Затем напишите функцию countChar, которая работает примерно как countBs, только принимает второй параметр — символ, который мы будем искать в строке (вместо того, чтобы просто считать количество символов “B”). Для этого переделайте функцию countBs.
                   <li>Сумма диапазона.  Напишите функцию range, принимающую два аргумента, начало и конец диапазона, и возвращающую массив, который содержит все числа из него, включая начальное и конечное.Затем напишите функцию sum, принимающую массив чисел и возвращающую их сумму. Запустите указанную выше инструкцию и убедитесь, что она возвращает 55.В качестве бонуса дополните функцию range, чтобы она могла принимать необязательный третий аргумент – шаг для построения массива. Если он не задан, шаг равен единице. Вызов функции range(1, 10, 2) должен будет вернуть [1, 3, 5, 7, 9]. Убедитесь, что она работает с отрицательным шагом так, что вызов range(5, 2, -1) возвращает [5, 4, 3, 2].
                      <li>Обращаем массив вспять. Напишите две функции, reverseArray и reverseArrayInPlace. Первая получает массив как аргумент и выдаёт новый массив, с обратным порядком элементов. Вторая работает как оригинальный метод reverse – она меняет порядок элементов на обратный в том массиве, который был ей передан в качестве аргумента. Не используйте стандартный метод reverse.
                         <li>Глубокое сравнение. Оператор == сравнивает переменные объектов, проверяя, ссылаются ли они на один объект. Но иногда полезно было бы сравнить объекты по содержимому. Напишите функцию deepEqual, которая принимает два значения и возвращает true, только если это два одинаковых значения или это объекты, свойства которых имеют одинаковые значения, если их сравнивать рекурсивным вызовом deepEqual. Чтобы узнать, когда сравнивать величины через ===, а когда – объекты по содержимому, используйте оператор typeof. Если он выдаёт “object” для обеих величин, значит нужно делать глубокое сравнение. Не забудьте об одном дурацком исключении, случившемся из-за исторических причин: “typeof null” тоже возвращает “object”.
                            <li>Свертка. Используйте метод reduce в комбинации с concat для свёртки массива массивов в один массив, у которого есть все элементы входных массивов.
   </ol>
Для реализации данной работы будет использоваться Visual Studio Code. Выполнение кода будет происходить в браузере Google Chrome.
</p>
<h2>Решение задач</h2>
<code>
	//1
      function func1(array, k) {
    let result = [];
    for (let i = 0; i < array.length; i++) {
        if (array[i] % k == 0)
            result.push(array[i]);
    }
    return result;
	}

	//2
	function func2(str1, str2) {
    str1 = str1.replace(/[^\w]/g, "").toLowerCase();
    str2 = str2.replace(/[^\w]/g, "").toLowerCase();

    let chars1 = str1.split("");
    let chars2 = str2.split("");

    if (chars1.length != chars2.length)
        return "не является аннограммой";

    chars1 = chars1.sort().join();
    chars2 = chars2.sort().join();

    if (chars1 === chars2) return "является аннограммой";
    return "не является аннограммой";
	}

	//3
	function func3(str) {
    let chars = ['a', 'e', 'i', 'o', 'u'];
    let count = 0;
    for (let i = 0; i < str.length; i++)
        if (chars.includes(str[i]))
            count++;
    return count;
	}

	//4
	function func4() {
    let str = "";
    for (let i = 0; i < 7; i++)
        console.log(str = str + "#");
	}

	//5
	function func5() {
    for (let i = 1; i <= 100; i++) {
        if (i % 3 == 0 && i % 5 == 0) {
            console.log('FizzBuzz');
            continue;
        }
        if (i % 3 == 0) {
            console.log('Fizz');
            continue;
        }
        if (i % 5 == 0) {
            console.log('Buzz');
            continue;
        }

        console.log(i);
    }
	}

	//6
	function func6() {
    let str = "";
    for (let i = 1, j = 1; i <= 64; i++) {
        if (j % 2 == 0)
            if (i % 2 == 0) str += "#";
            else str += " ";
        else
            if (i % 2 == 0) str += " ";
            else str += "#";

        if (i % 8 == 0) {
            str += "\n";
            j += 1;
        }
    }
    return str;
	}

	//7
	function func7() {
    let arg1 = parseInt(prompt('Первый аргумент'));
    let arg2 = parseInt(prompt('Второй аргумент'))
    console.log(min(arg1, arg2))
	}

	function min(arg1, arg2) // func7
	{
    return arg1 > arg2 ? arg2 : arg1;
	}

	//8
	function func8() {
    console.log("isEven(50) = " + isEven(50));
    console.log("isEven(75) = " + isEven(75));
    console.log("isEven(-1) = " + isEven(-1));
	}

	function isEven(num) // func 8
	{
    if (num == 1) return false;
    if (num == 0) return true;
    if (num > 0) return isEven(num - 2);
    if (num < 0) return isEven(num + 2);
	}

	//9
	function func9() {
    console.log(countBs(prompt("строка для подсчета символов 'B'")));
    console.log(countChar(prompt("строка для подсчета заданного символа"), prompt("символ")));
	}

	function countBs(str) // func 9
	{
    let count = 0;
    for (let i = 0; i < str.length; i++)
        if (str[i] == "B") count++;
    return count;
	}

	function countChar(str, char) 
	{
    let count = 0;
    for (let i = 0; i < str.length; i++)
        if (str[i] == char) count++; 
    return count;
	}

	//10
	function func10() {
    let start = parseInt(prompt("Start"));
    let end = parseInt(prompt("End"));
    let array = range(start, end);
    console.log(array);
    console.log(sum(array));

    start = parseInt(prompt("Start"));
    end = parseInt(prompt("End"));
    let step = parseInt(prompt("Step"));
    array = range(start, end, step);
    console.log(array);
    console.log(sum(array));
	}

	function range(start, end, step = 1) // func10
	{
    let array = [];
    for (let i = start; step < 0 ? i >= end : i <= end; i += step)
        array.push(i);
    return array;
	}

	function sum(array) // func10
	{
    let sum = 0;
    for (let i = 0; i < array.length; i++)
        sum += array[i];
    return sum;
	}

	//11
	function func11() {
    console.log(reverseArray([1, 2, 3, 4, 5, 6]));
    let array = [1, 2, 3, 4, 5, 6, 7];
    console.log(array);
    reverseArrayInPlace(array);
    console.log(array);
	}

	function reverseArray(array) // func11
	{
    let newArray = Array(array.length);
    for (let i = 0; i < array.length / 2; i++) {
        newArray[i] = array[array.length - i - 1];
        newArray[array.length - i - 1] = array[i];
    }
    return newArray;
	}

	function reverseArrayInPlace(array) // func11
	{
    for (let i = 0; i < array.length / 2; i++) {
        let temp = array[i] * 1;
        array[i] = array[array.length - i - 1];
        array[array.length - i - 1] = temp;
    }
	}

	//12
	function func12() {
    obj1 = {
        var1: "123",
        var2: 123,
        var3: [1, 2, 3]
    }

    obj2 = {
        var1: "123",
        var2: 123,
        var3: [1, 2, 3]
    }

    obj3 = {
        var1: 1234,
        asdad: [1, 2, 3, 4],
        var3: "привет"
    }

    console.log("deepEqual(123,123) = " + deepEqual(123, 123));
    console.log("deepEqual(445,123) = " + deepEqual(445, 123));
    console.log("deepEqual('123','123') = " + deepEqual('123', '123'));
    console.log("deepEqual('445','123') = " + deepEqual('445', '123'));
    console.log("deepEqual(obj1, obj2) = " + deepEqual(obj1, obj2));
    console.log("deepEqual(obj1, obj3) = " + deepEqual(obj1, obj3));
    console.log("deepEqual(obj1, null) = " + deepEqual(obj1, null));
    console.log("deepEqual(null, null) = " + deepEqual(null, null));

	}

	function deepEqual(arg1, arg2) {
    if (typeof (arg1) != 'object' && typeof (arg2) != 'object') return arg1 === arg2;

    if (arg1 == null && arg2 == null) return true;
    if (arg1 == null || arg2 == null) return false;

    let keys1 = Object.keys(arg1);
    let keys2 = Object.keys(arg2);

    if (keys1.length != keys2.length) return false;

    for (key of keys1)
        if (!keys2.includes(key) || !deepEqual(arg1[key], arg2[key])) return false;

    return true;
	}

	//13
	function func13() {
    let array = [
        [1, 2, 3],
        [4, 5],
        [6, 7, 8, 9],
        [10, 11, 12, 13, 14, 15, 16, 17, 18, 19],
        [20]
    ]
    console.log(array.reduce((a, b) => a.concat(b)));
	}

</code>
<h2>Вывод</h2>
<p>В ходе лабораторной работы были изучены элементы языка Java script. Были рассмотрены способы задания переменных, операций над ними, была проведена работа с циклами и функциями. Результатом лабораторной работы являются решенные задачами.</p>    
