# OSPF

Статей и видео о том, как настроить OSPF горы. Гораздо меньше описаний принципов работы. Вообще, тут такое дело, что OSPF можно просто настроить согласно мануалам, даже не зная про алгоритмы SPF и непонятные LSA. И всё будет работать и даже, скорее всего, прекрасно работать — на то он и рассчитан. То есть тут не как с вланами, где приходилось знать теорию вплоть до формата заголовка.  
Но инженера от эникейщика отличает то, что он понимает, почему его сеть функционирует так, а не иначе, и не хуже самогo OSPF знает, какой маршрут будет выбран протоколом.  
В рамках статьи, которая уже на этот момент составляет 8 000 символов, мы не сможем погрузиться в глубины теории, но рассмотрим принципиальные моменты.  
Очень просто и понятно, кстати, написано про OSPF на [xgu.ru](http://xgu.ru/wiki/OSPF) или в английской [википедии](http://en.wikipedia.org/wiki/Open_Shortest_Path_First).  
Итак, OSPFv2 работает поверх IP, а конкретно, он заточен только под IPv4 \(OSPFv3 не зависит от протоколов 3-го уровня и потому может работать с IPv6\).

