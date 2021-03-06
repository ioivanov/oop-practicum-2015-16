# Упражнение 2

## Задача 1. Двуизмерна точка

Да се реализира представяне на двуизмерна точка.

- Да се използва структура с две полета от тип `double` - `x`, `y` - за 
двете координати на точката
  - Да се реализира функция за транслиране на точката по дадени отмествания `dx`, `dy`
  - Да се реализира функция за пресмятане на разстояние между две точки

- Да се използва същата структура
  - Да се реализира метод на структурата за транслиране на точката по дадени отмествания `dx`, `dy`
  - Да се реализира метод на структурата за пресмятане на разстояние между точката и друга точка

- Същата структура, да се използва като се замени с `class`
  - Полетата за координатите да са `private`
  - Да се реализират `public` селектори и мутатори за координатите на точката
  - Методите за транслиране и намиране на разстояние да използват публичните селектори и мутатори

## Задача 2. Последователност

Да се реализира представяне на последователност от цели числа (`Sequence`) със следните функционалности:

- възможност за намиране на сумата на всички членове на последователността
- възможност за намиране на броя на различните от 0 членове на последователността
- възможност за намиране на първия по-голям от 0 елемент на последователността
