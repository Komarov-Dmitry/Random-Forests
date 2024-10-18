# Проект: Классификация и Регрессия с использованием Случайных Лесов

## Описание проекта

Данный проект посвящен изучению алгоритма Случайных Лесов (Random Forest) как для задач классификации, так и для регрессии. Мы также проводим сравнительный анализ различных методов регрессии, чтобы понять их эффективность в решении задачи предсказания.

## Содержание

1. [Часть 1: Классификация с использованием случайных лесов](#часть-1-классификация-с-использованием-случайных-лесов)
2. [Часть 2: Регрессия с использованием случайных лесов](#часть-2-регрессия-с-использованием-случайных-лесов)
3. [Сравнительный анализ методов регрессии](#сравнительный-анализ-методов-регрессии)
4. [Заключение](#заключение)

## Часть 1: Классификация с использованием случайных лесов

### Данные

Мы используем набор данных "Palmer Penguins" для классификации видов пингвинов на основе их физических атрибутов. Данные содержат следующие переменные:

- species: разновидности пингвинов (Chinstrap, Adélie, Gentoo)
- culmen_length_mm: длина клюва (мм)
- culmen_depth_mm: высота клюва (мм)
- flipper_length_mm: длина крыла (мм)
- body_mass_g: масса тела (г)
- island: название острова
- sex: пол пингвина

### Цель

Создать модель классификации, которая поможет определять вид пингвина на основе его физических атрибутов, упрощая работу исследователей без привлечения опытного биолога.

### Исследование гиперпараметров

Мы исследуем влияние гиперпараметров случайного леса, таких как количество деревьев (Number of Estimators), и визуализируем зависимость ошибок от количества деревьев.

## Часть 2: Регрессия с использованием случайных лесов

### Данные

Используются данные буровой компании для предсказания плотности камня по отраженному сигналу на различных частотах. Это помогает в оптимизации замены буровых головок.

### Цель

Определить наиболее эффективную модель регрессии для предсказания изменения плотности камня.

## Сравнительный анализ методов регрессии

Для выполнения задачи регрессии были использованы следующие модели:

1. Линейная регрессия
2. Полиномиальная регрессия
3. Пайплайн для степеней полинома
4. Регрессия KNN
5. Деревья решений для регрессии
6. Метод опорных векторов для регрессии
7. Случайные леса для регрессии
8. Градиентный бустинг
9. Adaboost

Мы сравниваем производительность каждой модели, оценивая их точность и ошибки на тестовых данных.

## Заключение

В проекте были изучены возможности алгоритма случайных лесов для классификации и регрессии. Сравнительный анализ различных методов регрессии позволил выявить их сильные и слабые стороны в контексте специфической задачи.
