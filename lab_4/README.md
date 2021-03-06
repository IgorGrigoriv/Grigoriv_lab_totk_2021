# Звіт по лабораторній роботі №4
---
### із дисципліни Теоретичні основи телекомунікацій
## Тема: *Алгоритми пошуку найкоротших шляхів*
---
## Мета роботи: *Навчитись застосовувати алгоритми пошуку найкоротших шляхів та застосовувати їх в телекомунікаційних мережах.*

### Виконав: студент групи ТР-32 Григорів І.І.
### Прийняв: викладач Бугиль Б.А.
---

### Виконання роботи
#### 1.	За допомогою лабораторного макету побудувати випадковий неорієнтований зважений граф з V=6 та E=10 та побудувати дерево шляхів з вершини N за алгоритмом Дейкстри;

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_4/1.png)

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_4/2_1.png)




#### 2.	Для того ж графа побудувати дерево шляхів з вершини N за алгоритмом Беллмана-Форда;

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_4/3.png)

#### 3.	Вказати який з алгоритмів виконується швидше:
* Швидше виконується алгоритм Дейкстри.

##### i.	порівняти за кількістю кроків для знаходження найкоротшого шляху;
* Дейкстри – 5 кроків, Беллмана-Форда – 6 кроків.

##### ii.	порівняти за кількістю відвіданих вершин на кожному кроці;
* Дейкстри – 9 вершин, Беллмана-Форда – 20 вершин.

#### 4.	Чи знайдені маршрути за алгоритмом Дейкстри та Беллмана-Форда однакові?
* Так.

##### ii.	Чи існують маршрути з однаковою метрикою? Які?
* Ні.

### 5.	Вважаючи, що коефіцієнти ребер вказують на пропускну здатність в Мбіт/с, знайти пропускну здатність кожного шляху визначеного за алгоритмом Дейкстри та Беллмана-Форда.
* Так як дерева алгоритмів Дейкстри та Белламана-Форда однакові, відповідно пропускна здатність буде теж однаковою:

![image](https://github.com/IgorGrigoriv/Grigoriv_lab_totk_2021/blob/main/lab_4/4.png)

##### i.	Які шляхи мають максимальну пропускну здатність, чому?
* Шлях від вершини 0 до вершини 3 із пропускною здатністю 11 Мбіт/с, тому що у нього на дорозі немає вершин із меншою пропускною здатністю.

##### ii.	Чи є шляхи які на якомусь відрізку мережі використовують менше половини пропускної здатності ребра?
* Так: шлях від вершини 0-1-2 шлях.

##### iii.	Чи можливе одночасне існування потоків із вершини N до всіх інших із розрахованою пропускною здатністю кожного шляху? Чому?
* Ні, тому що щоб пройти 0-1-2 потрібно 8 Мбіт/с а, вершина 1 пропускає лише 3 Мбіт/с, 0-3-4 потрібно 16 Мбіт/с а, вершина 3 пропускає лише 11 Мбіт/с, 0-5-4 потрібно 5 Мбіт/с а, вершина 5 пропускає 2 Мбіт/с.
