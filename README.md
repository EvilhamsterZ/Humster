# Сабуров Сергей Фт-200008
Прикладное программирование курс
С++ Visual Studio 2019
## Code
```
include <iostream>
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

int main()
{
    float c;
    float a;
    float b;
    /*Объявление переменных с плавающей точкой для возможности подсчета среднего арифмитического*/
    cin >> a;
    cin >> b;
    c=sum(a, b);
    /*выполняем первую функцию суммы*/
    cout << c <<endl;
    /*вывод суммы*/
    c = raz(a, b);
    /*функция разности*/
    cout << c <<endl;
    /*вывод разности*/
    c = sred(a, b);
    /*среднее арифметическое*/
    cout << c << endl;
    /*вывод среднего */
    return 0;
}
```
