# JAVA_TASK3.1
A simple program to demonstrates regular expressions in java.
String sort(String str) 
Переставляет слова в строке str в порядке уменьшения их размера и возвращает результат преобразования. Строка str - предложение без знаков препинания.

Пример работы:

sort("a bbb cccc ddd e"); // "cccc bbb ddd a e"

boolean isPhone(String str) 	Проверяет, является ли строка str корректным строковым представлением номера телефона, и возвращает результат проверки. Строка str - строковое представление номера телефона.

Корректное строковое представление номера телефона начинается с международного кода страны, записанной со знаком плюс. За ним следует префикс из 3 цифр, указанный в скобках, обозначающий код оператора или регион регистрации номера. Строковое представление завершается номером абонента из 7 цифр, записанных в формате 123-45-67.

Пример работы:
isPhone("+7(123)456-78-90"); // true
isPhone("81234567890"); // false
