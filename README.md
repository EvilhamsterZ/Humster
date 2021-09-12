# Сабуров Сергей Фт-200008
Прикладное программирование
## Среда Разработки
С++ Visual Studio 2019

## Программа для работы с двумя переменными
Это название программы

### Описание
Программа умеет считать частное, произведение, сумму, разность и среднее арифмитическое двух переменных
```
#include <iostream>
using namespace std;

float sum(float a, float b)/* функция для суммы двух переменных*/
{
    return a + b;
}
float raz(float a, float b)/* функция для разности двух переменных*/
{
    return a - b;
}
float sred(float a, float b)/* функция для среднего арифмитического для двух переменных*/
{
    return (a + b)/2;
}
float proizv(float a, float b)/* функция для произведения для двух переменных*/
{
    return a*b;
}
float chastnoe(float a, float b)/* функция для среднего частного для двух переменных*/
{
    return a/b;
}

int main()
{   
    setlocale(LC_ALL, "RUS");
    /*Добавим русский вывод для красоты программы*/
    float c;
    float a;
    float b;
    /*Объявление переменных с плавающей точкой для возможности подсчета среднего арифмитического*/
    cout << "Введите первую переменную: ";
    cin >> a; 
    cout << "Введите вторую переменную: ";
    cin >> b;
    c=sum(a, b);
    /*выполняем первую функцию суммы*/
    cout <<"Сумма = " << c << endl;
    /*вывод суммы*/
    c = raz(a, b);
    /*функция разности*/
    cout << "Разность = " << c <<endl;
    /*вывод разности*/
    c = sred(a, b);
    /*среднее арифметическое*/
    cout << "Среднее арифмитическое = " << c << endl;
    /*вывод среднего */
    c = proizv(a, b);
    /*произведение*/
    cout << "Произведение = " << c << endl;
    /*вывод произведения */
    c = chastnoe(a, b);
    /*частное*/
    cout << "Частное = " << c << endl;
    /*вывод частного */
    return 0;
}
```
### Скрин отладки
(![скрин](https://user-images.githubusercontent.com/90544365/132997800-895ed2ac-991e-42dc-83d3-fb87cd56954b.jpg)
