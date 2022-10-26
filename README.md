# Golden-Ball Девятая программа: «Золотой мяч»

Кекс уважает футбол, но смотреть игры ему лень некогда. Но это не страшно, ведь коту достаточно знать имена лучших бомбардиров и их результативность, чтобы поставить на игрока поддержать беседу в нужный момент.

Пока вы писали игру, на почту пришло письмо от Кекса с пометкой «Надо было ещё вчера».

Мяу! Мне нужна программа, которая подсчитает полезность и результативность игроков на основе их статистики. Оформи код в виде функции getStatistics с одним параметром — массивом игроков.

Каждый футболист в этом массиве описывается объектом с тремя полями: имя (свойство name), забитые голы (свойство goals) и голевые пасы (свойство passes).

Функция должна возвращать этот же массив, в котором каждому игроку добавлены ещё два поля: коэффициент полезности по Кексу® (свойство coefficient) и результативность (свойство percent).

Коэффициент полезности считается так: умножаем голы игрока на 2 (потому что я считаю, что голы важнее всего) и прибавляем к этому значению все голевые пасы футболиста.
Результативность (процент забитых мячей футболиста от результата всей команды) считаем так: находим сумму голов всех игроков и выясняем, сколько процентов от этого числа забил каждый футболист. Округляй значение с помощью Math.round.


Скрыть подсказку
Рассчитываем, какой процент составляет число:

// Общее значение, то есть 100%
1200
// Сколько процентов составляет 225 от 1200
(225 * 100) / 1200 = 18.75
// После округления с помощью Math.round
19
