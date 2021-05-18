Модель работы супермаркета 
Необходимо разработать имитационную модель обслуживания покупателей супермаркета несколькими (1≤ K ≤ 7) кассами супермаркета. 
Супермаркет работает круглосуточно. 
При моделировании работы супермаркета/магазина его покупатели приходят случайным образом: случайной величиной является отрезок 
времени между последовательным появлением двух покупателей. Эта случайная величина имеет нормальное или равномерное распределение 
в некотором интервале (например, от 0 до 7 минут), причем плотность потока заявок зависит от дня недели, времени дня и величины 
очередей у касс/продавцов (в конце недели и в конце дня клиенты приходят чаще, плотность потока выше). Длительность обслуживания 
каждого покупателя также случайное число в некотором диапазоне (например, от 1 до 7 минут), но оно не зависит от входного потока 
заявок. Еще одной случайной величиной является сумма покупки (от 50 руб. до 5 тыс. руб.), причем сумма не зависит от других 
случайных величин. 
Максимально возможная длина очереди у каждой кассы – N человек (5≤ N ≤ 8), не считая обслуживаемого покупателя. Очереди формируются 
по определенному закону – так, что разница между максимальной и минимальной очередью у касс не превышает три человека. Если у 
каждой кассы скопилась очередь из N человек, то вновь прибывающие покупатели уходят, и вероятность прихода следующих уменьшается – 
тем самым супермаркет теряет своих потенциальных покупателей. 
Цель исследования работы супермаркета – определение оптимальных режимов его работы, т.е. режимов, при которых работающие кассы или 
продавцы всегда заняты, и увеличиваются прибыли от продаж. Режим работы включает число касс, рекламу и скидки на товары. 
Считается, что затрата 7 тыс. руб. в день на рекламу увеличивает поток покупателей на 10%, а при объявлении скидок на товары каждый 
процент скидки увеличивает плотность потока на 0.5%. Известна также средняя прибыль, получаемая при обслуживании каждого покупателя – 
30 % от стоимости покупки, и дневная зарплата каждого кассира (1.5тыс.руб.).
Период моделирования – неделя, шаг – интервал времени от 10 до 60 минут. Кроме шага, в параметры моделирования следует включить числа 
K и N, диапазоны разброса случайных величин – стоимости покупки, а также затраты на рекламу, величину скидки, прибыль от суммы покупки 
в 1 тыс. руб., зарплату кассира или продавца и степень уменьшения потока покупателей при возникновении максимальной очереди. 
Визуализация моделируемого процесса должна предусматривать показ очередей у каждой кассы, а также вывод статистической информации, 
собираемой в ходе моделирования: количество обслуженных и потерянных (потенциальных) покупателей, средняя длина очереди у касс и 
среднее время обслуживания в ней, общая прибыль, полученная супермаркетом. 