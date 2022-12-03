# Символни низове.

## Въведение в символните низове (стрингове).

   ```c++
	char str[] = {'t', 'e', 's', 't', '\0'};
	char str2[] = "test"; //equivalent to str
	char str3[7] = "test"; 
```

![enter image description here](https://i.ibb.co/ZmRwt6R/Untitled-Diagram-drawio-5.png)

Примерна имплементация на:

 - strlen (намиране на дължина на стринг)
 - strcpy (копиране на стринг)
 - strcat (конкатениране на стрингове)
 - strcmp (лексикографско сравнение на стрингове)
 - atoi (преобразуване на стринг в число)
 - търсене в текст
 - броене на срещанията на конкретен символ в текст
 - заместване в стринг.


 - Да се напише функция, която приема такъв стринг и връща нов стринг с ТОЧНА ГОЛЕМИНА, в който всички цифри са цензурирани. (Всяко число е заменено с '*')
 - Да се напише функция, която приема стринг и връща два стринга с ТОЧНА големина. Първият да бъде съставен само от малките букви, а другият да бъде съставен само от главните букви.

<h3>Задачи</h3>

**Задача 1:** Напишете функция, която приема 3 стринга - text, where и what и земства в text всяко срещане на where с what.

*Да се реши без допълнителна памет (in-place).*

*Вход: "I am the best of the best", "best" , "worst" , Изход: "I am the worst of the worst"*

**Задача 2** Напишете функции toUpper и toLower, които приемат стринг и променят всички главни букви в малки/всички малки букви в главни.

**Задача 3** Напишете функция, която приема стринг и връща броя на думите в него. (Думите са разделени с произволен брой интервали, табулации и препинателни знаци)

*Вход: "Me? Why always me?, Изход: 4*


**Задача 4** Напишете функция, която приема стринг и връща най-често срещаната дума.(Думите са разделени с произволен брой интервали, табулации и препинателни знаци). Игнорираме разликата между главни и малки букви за задачата.

*Вход: "Me? Why always me?, Изход: me*

**Задача 5** Напишете функция, която приема стринг и връща лексикографско най-малка дума.

*Вход: "Me? Why always me?, Изход: always*
