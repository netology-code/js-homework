# Домашнее задание к лекции 1.3 «Циклы»

На ваш склад поступила большая партия разнообразных товаров. Наименований много, и вас попросили написать программу для проведения инвентаризации, чтобы облегчить работу кладовщику.

## Перед началом работы
1. Активируйте строгий режим соответствия.
2. Скопируйте код ниже и вставьте его в начало своей работы:

```javascript      
var positions = [
  'Отвертка ультразвуковая WHO-D',
  'Ховерборд Mattel 2016',
  'Нейтрализатор FLASH black edition',
  'Меч световой FORCE (синий луч)',
  'Машина времени DeLorean',
  'Репликатор домашний STAR-94',
  'Лингвенсор 000-17',
  'Целеуказатель электронный WAY-Y'
]
```      
    
## Задача № 1
Для начала выведем список товаров, по которому кладовщик будет проводить инвентаризацию.

### Процесс реализации
1. Создайте переменную и присвойте ей значение длины массива.
2. Перед списком выведите в консоль фразу `Список наименований`.
3. Напишите цикл, который в каждой итерации будет выводить номер товара и его название из списка в формате `1 'Отвертка ультразвуковая WHO-D'`.
4. Нумерация в списке должна начинаться с 1.
5. Цикл должен продолжать работу, пока не достигнет конца списка.

## Задача № 2
Оказалось, что привезли не все товары. После небольшого разбирательства прибыл еще один корабль и доставил недостающие позиции. Нужно добавить их в список к уже имеющимся товарам.

### Процесс реализации
1. Добавьте в конец списка следующие товары:
   * Экзоскелет Trooper-111
   * Нейроинтерфейс игровой SEGUN
   * Семена дерева Эйва
2. Перед вторым списком выведите фразу `Окончательный список наименований`.
3. Выведите в консоль новый получившийся список в том же формате, что и в задаче № 1.

## Задача № 3
На некоторые товары уже поступил предзаказ. Их нужно принять в первую очередь. Напишите код, который будет искать название товара в списке наименований и передвигать его на первое место.

### Процесс реализации
1. Первым нужно принять товар с названием `'Машина времени DeLorean'`.
2. Найдите этот товар в списке и запишите его индекс в новую переменную.
3. Используя переменную с индексом, вырежьте найденный товар с его позиции.
4. Переместите вырезанный товар в начало списка.
5. Выведите первые три товара в консоль под заголовком `Принять в первую очередь`.
*Не забудьте, что `splice` возвращает массив.*

## Задача № 4. Дополнительная (необязательная)
Новые товары нужно разместить в интернет-магазине. Контент-менеджеру для заведения информации о товарах на сайт общий список не подходит. Нам нужно подготовить несколько товаров в виде отдельных переменных. Работать мы будем с массивом, полученным в итоге выполнения всех трех предыдущих задач.

### Процесс реализации
1. Получите первые пять наименований товаров и запишите их в новые переменные.
2. Оставшиеся элементы массива не должны отбрасываться.
3. Выведите в консоль каждую из пяти новых переменных под заголовком `В магазине`.
4. Оставшиеся товары выведите в консоль под заголовком `Остальные товары`.
Решите задачу, максимально используя возможности **ES2015**.

---
Инструкция по выполнению домашнего задания:

1. Зарегистрируйтесь на сайте [Repl.IT](https://repl.it/).
2. Перейдите в раздел **my repls**.
3. Нажмите кнопку **Start coding now!**, если приступаете впервые, или **New Repl**, если у вас уже есть работы.
4. В списке языков выберите JavaScript.
5. Код пишите в левой части окна.
6. Посмотреть результат выполнения файла можно, нажав на кнопку **Run**. Результат появится в правой части окна.
7. После окончания работы нажмите кнопку **Share** и скопируйте ссылку из поля *Share link*.
8. В личном кабинете на сайте [netology.ru](http://netology.ru/) в поле комментария к домашней работе вставьте скопированную ссылку и отправьте работу на проверку.

*Никаких файлов прикреплять не нужно.*