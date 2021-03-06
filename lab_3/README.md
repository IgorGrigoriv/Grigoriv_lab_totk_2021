# Звіт із лабораторної роботи №3
---
### із дисципліни Теоретичні основи телекомунікацій
## Тема: *Методи обходу та модифікації графів.*
---
## Мета роботи: *Навчитись застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева.*

### Виконав: студент групи *ТР-32* Григорів І.І.
### Прийняв: викладач Бугиль Б.А.
---

### Виконання роботи
#### 1.	За допомогою лабораторного макету побудувати випадковий неорієнтований граф G={8,12}:

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/1_1.png)

i.	Побудувати дерево за алгоритмом обходу в ширину (BFS); (для 2-х різних вершин)
* Для вершини 0 порядок обходу: 0 1 2 7 3 6 4 5

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/1_2.png)

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/1_3.1.png)

* Для вершини 5 порядок обходу: 5 4 6 7 3 2 0 1

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/1_4.png)

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/1_5.png)

ii.	Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?
* Так, тому що на виході із вершини 0 і 5 корінь в обох має по три вершини.

iii.	Побудувати дерево за алгоритмом обходу в глибину (DFS); (для 2-х різних вершин)
* Для вершини 7 порядок обходу: 7 0 1 3 4 5 6 2

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/2_1.png)

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/2_2.png)

* Для вершини 6 порядок обходу: 6 2 0 1 3 4 5 7

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/2_3.png)

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/2_4.png)

iv.	Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?
* Так.

#### 2.	За допомогою лабораторного макету побудувати випадковий орієнтований граф G={6,10}:

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/2_5.png)

i.	Побудувати дерево за алгоритмом обходу в ширину (BFS);
* Порядок обходу:  0 1 5 2 4 3

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/2_6.png)

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/2_7.png)

ii.	Яка вершина (вершини) буде знайдена останньою?
* Вершина 3

iii.	Визначити чи існують цикли. Вказати послідовність ребер і їх довжину.
* Цикли: Немає циклів.

iv.	Визначити кількість хвиль, які пройдуть по ребрах доки буде виявлена остання вершина.
* Кількість хвиль становить 5.

v.	Побудувати дерево за алгоритмом обходу в глибину (DFS);
* Порядок обходу: 0 1 2 3 4 5

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/3_2.png)

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/3_3.png)

#### 3.	Побудувати дерево шляхів рангом r=4 для випадкового графа G={6,9}.

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/4_1.png)


![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/4_2.png)


#### 4.	Побудувати мінімальне зв’язне дерево для графа G. Вказати його вагу.

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/4_3.png)


![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_3/4_4.png)

* Вага: 5+7+9+3+5=29
