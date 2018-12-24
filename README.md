# lab_practice

5 курс, лабораторный практикум.

Реализация программы для рассчета фактора эффективности выметания
однородных сферческих однослойных частиц излучением звёзд.

На вход прогамма принимает температуру, массу и радиус звезды,
плотность пыли. Также на вход подаются файлы **Qpr_carbon.dat**
или **Qpr_silicat.dat**, в которых содержатся рассчеты фактора
**Qpr** для углеродных и силикатных частиц соответственно. Первый 
столбец - длина волны в мкм, остальные - **Qpr** для разнх размеров
пылинок. (размеры в порядке следования столбцов указаны в файле
**sizes.dat**)

Подробный отчет по этой задаче см. в файле **MIEtheory.pdf**.