# Звіт по лабораторній роботі №5
---
### із дисципліни Теоретичні основи телекомунікацій
## Тема: *Визначення максимального потоку*
---
## Мета роботи: *Навчитись знаходити максимальний потік між парою вузлів та визначати мінімальний переріз.*

### Виконав: студент групи *ТР-32* Крупський А.С.
### Прийняв: викладач Бугиль Б.А.
---

### Виконання роботи
#### 1.	За допомогою лабораторного макету побудувати випадковий неорієнтований зважений граф G={8,10}.

![image](https://user-images.githubusercontent.com/69114727/118403683-349d8000-b678-11eb-91d8-b16f93965277.png)

#### 2.	Знайти шлях (вказати послідовність ребер) з максимальною пропускною здатністю (вказати якою) між вузлами i та j (i - вершина витоку (початкова); j - вершина стоку (кінцева)).

![image](https://user-images.githubusercontent.com/69114727/118403695-467f2300-b678-11eb-8519-6334d2dd4c9d.png)

![image](https://user-images.githubusercontent.com/69114727/118403712-5434a880-b678-11eb-8999-51db67f4e488.png)

![image](https://user-images.githubusercontent.com/69114727/118403763-9c53cb00-b678-11eb-83c1-6c9e27a5882d.png)


* Послідовність ребер: 7-5-3-6-8; пропускна здатність (максимально): 8. 

#### 3.	Визначити максимальний потік, який може бути переданий між вузлами i та j.
* Максимальний потік становить 8+1+1=10

#### 4.	Вказати ребра, які входять у мінімальний переріз (Переріз - видаляємо ребра графа так щоб не було шляхів між витоком і стоком).
* Ребра витоку 2=>5 та 0=>3.

#### 5.	Визначити максимальний потік, який може виходити з вузла i. Визначити максимальний потік, який може входити у вузол j.
* Для вузла і:12; для вузла j: j = 14.

#### 6.	Вважаючи, що між вузлами i та j передається максимальний потік, до яких вузлів можна здійснити передачу інформації з вузла і. Визначити пропускну здатність даних маршрутів.
* 6.	Передати інформацію до інших вузлів неможливо.

#### 7.	Вважаючи, що між вузлами i та j передається максимальний потік, які вузли можуть здійснити передачу інформації до вузла j. Визначити пропускну здатність даних маршрутів.
* Маршрути до вузла j та їх пропускні здатності:  
* 6 – 8 = 4;  
* 4 - 6 – 8 = 4;  
* 1 - 4 - 6 – 8 = 4;  
* 3 - 1 - 4 - 6 – 8 = 3;  
* 0 - 3 - 1 - 4 - 6 – 8 = 1;  

