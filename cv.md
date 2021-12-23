# **Еркебаев Нурсултан** 
#### Мужчина, 26 лет, родился 16 апреля 1995

### +7(707) 2839405
* [erkebaevnursultan@gmail.com]()
* Проживает: Нур-Султан
* Гражданство: Казахстан, есть разрешение на работу: Казахстан

# **Образование**
## *Высшее*
### Евразийский национальный университет имени Л. Н. Гумилёва, Нур-Султан
Физика технический факультет, Радиоэлектронника и телекоммуникация

## **Ключевые навыки**
## *Навыки:*
* Java core
* SQL
* Git
* HTML/CSS
* JavaScript

## *Знание языков*
* Казахский — Родной
* Английский — B1 — Средний
* Русский — B2 — Средне-продвинутый

# **Дополнительная информация**
## *Обо мне*
### В данный момент обучаюсь в центре программирования Runtime.
## Что изучил:
1. Язык программирования Java
2. Структуры данных и алгоритмы (сортировка массива - 3 варианта), бинарный поиск и тд).
```java
int[] arr = {10, 8, 9, 2, 3, 5, 6, 4, 7, 1};
System.out.println(Arrays.toString(arr));

System.out.println("\nСортировка выбор");
for (int i = 0; i < arr.length; i++) {
    int minVal = arr[i];
    int minInd = i;
    for (int j = i + 1; j < arr.length; j++) {
        if (arr[j] < minVal) {
            minVal = arr[j];
            minInd = j;
        }
    }
    int tmp = arr[i];
    arr[i] = minVal;
    arr[minInd] = tmp;
    System.out.println(Arrays.toString(arr));
}
```
3. HTML, CSS (верстка), есть свой сайт портфолио enur.runtime.kz
4. SQL (СУБД PostgreSQL)
```SQL
CREATE TABLE Departments (
   Code INTEGER PRIMARY KEY NOT NULL,
   Name NVARCHAR NOT NULL,
   Budget REAL NOT NULL 
 );
 
 CREATE TABLE Employees (
   SSN INTEGER PRIMARY KEY NOT NULL,
   Name TEXT NOT NULL,
   LastName VARCHAR NOT NULL, --since question 2 asks about removing duplicate - text must be converted if the answer is using distinct
   Department INTEGER NOT NULL, 
   CONSTRAINT fk_Departments_Code FOREIGN KEY(Department) 
   REFERENCES Departments(Code)
 );
 
 INSERT INTO Departments(Code, Name, Budget) VALUES(59, 'Human Resources', 240000);
 INSERT INTO Departments(Code, Name, Budget) VALUES(77, 'Research', 55000);

 INSERT INTO Employees(SSN, Name, LastName, Department) VALUES('123234877', 'Michael', 'Rogers', 14);
 INSERT INTO Employees(SSN, Name, LastName, Department) VALUES('152934485', 'Anand', 'Manikutty', 14);
```
5. Git

## *О личных качеств*
- Умею находить общий язык с незнакомыми людьми;
- Сохраняю спокойствие в любой ситуации;
- Эффективно работаю в режиме многозадачности;
- Не имею вредных привычек;
- Уверенный в себе;
- Исполнительный;

### **А также есть аккаунт в GitHub с практическими проектами** - [account](https://github.com/Erkebaev95)

