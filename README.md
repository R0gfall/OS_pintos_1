# OS_pintos_1
lab_1 PintOS release timer_sleep()

Реализация функции timer_sleep() без активного ожидания, так же было добавлено два теста:
3) ticks_stats - подсчет количество тиков 10 процессов в состоянии TIME_RUNNING, с использованием timer_sleep(100) и 10 итераций (Было создано 10 процессов, исполняющие бесконечные циклы)
4) max-mem-malloc, max-mem-calloc, max-mem-palloc - подсчет количества памяти, выделяемые ядром PintOS разными способами
