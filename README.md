# Filter-Kalman

## Стандартні параметри F H Q R P X

Noise Variance Before Filtering: 16.03<br>
Noise Variance After Filtering: 2.93

![](/screenshots/1.png)

## Матриця коваріації оцінки P

### Параметр (P-1) замінив (P-0)

Noise Variance Before Filtering: 17.50<br>
Noise Variance After Filtering: 2.86

Змінюючи P, фільтр почав повільніше адаптуватися до змін стану, орієнтуючись більш на вимірюванні.

![](/screenshots/2.png)

## Матриця коваріації оцінки P

### Параметр (P-1) замінив (P-50)

Noise Variance Before Filtering: 15.68<br>
Noise Variance After Filtering: 2.40

Після фільтрації результати залишаються подібними до P=0 але адаптація відбувається швидше.

![](/screenshots/3.png)

## Матриця коваріації шуму процесу Q

### Параметр (Q-1) замінив (Q-0)

Noise Variance Before Filtering: 17.83<br>
Noise Variance After Filtering: 10.90

Фільтр дуже повільно адаптується до змін.

![](/screenshots/4.png)

## Матриця коваріації шуму процесу Q

### Параметр (Q-1) замінив (Q-15)

Noise Variance Before Filtering: 16.22<br>
Noise Variance After Filtering: 8.26

Збільшення Q робить фільтр більш чутливим до нових вимірювань. Це зменшує плавність графіка, але покращує адаптацію до швидких змін.

![](/screenshots/5.png)

## Матриця коваріації шуму вимірювань R

### Параметр (R-10) замінив (R-100)

Noise Variance Before Filtering: 16.06<br>
Noise Variance After Filtering: 1.65

Результат фільтрації згладжений, менше реагуе на шумні вимірювання.

![](/screenshots/6.png)

## Матриця коваріації шуму вимірювань R

### Параметр (R-10) замінив (R-0)

Noise Variance Before Filtering: 15.24<br>
Noise Variance After Filtering: 15.24

Графік фільтрованих даних дуже чутливі до кожного нового вимірювання,фільтровані дані майже ідентичні шумним вимірюванням.

![](/screenshots/7.png)
