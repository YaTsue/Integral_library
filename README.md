Библиотека создана в рамках статьи "Интеграл и игровые движки"
Цель разработки: создать библиотеку с численными методами интегрирования, применяемые в создании игровых движков на С++
При создании игровых движков самым популярным и мощным языком программирования является С++. При работе с 3Д графикой движка возникает большое количество математических, физических, уравнений и формул, которые требуется
интегрировать для создания эффекта. На данный момент С++ не имеет библиотеки интегралов, поэтому различным командам приходится каждый раз прописывать такую библиотеку , причем очень часто используя одни и те же
методы интегрирования. Для того, чтобы облегчить и ускорить разработку таких проектов мы решили начать разработку  библиотеки.
В дальнейшем библиотека будет пополняться необходимыми и универсальными методами интегрирования. На данный момент библиотека содержит 5 методов:
1 - метод прямоугольников 
2 - метод трапеций 
3 - метод Симпсона
4 - метод Эйлера
5 - метод Верле