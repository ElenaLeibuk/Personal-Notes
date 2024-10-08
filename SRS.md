# Требования к проекту
---

# Содержание
1 [Введение](#intro)  
1.1 [Назначение](#appointment)  
1.2 [Бизнес-требования](#business_requirements)  
1.2.1 [Исходные данные](#initial_data)  
1.2.2 [Возможности бизнеса](#business_opportunities)  
1.2.3 [Границы проекта](#project_boundary)  
1.3 [Аналоги](#analogues)  
2 [Требования пользователя](#user_requirements)  
2.1 [Программные интерфейсы](#software_interfaces)  
2.2 [Интерфейс пользователя](#user_interface)  
2.3 [Характеристики пользователей](#user_specifications)    
2.4 [Предположения и зависимости](#assumptions_and_dependencies)  
3 [Системные требования](#system_requirements)  
3.1 [Функциональные требования](#functional_requirements)   
3.2 [Нефункциональные требования](#non-functional_requirements)  

<a name="intro"/>

# 1 Введение

<a name="appointment"/>

## 1.1 Назначение
В этом документе описаны функциональные и нефункциональные требования к мобильному приложению «Личные заметки» для ОС Android. 

<a name="business_requirements"/>

## 1.2 Бизнес-требования

<a name="initial_data"/>

### 1.2.1 Исходные данные
В современном мире, где информация поступает к нам со всех сторон, важно иметь удобный инструмент для организации и хранения личных записей. Приложение "Личные заметки” создано для того, чтобы помочь вам эффективно управлять своими заметками, идеями и задачами. В зависимости от того, студент вы, профессионал или просто человек, стремящийся к порядку в своей жизни, наше приложение станет вашим надежным помощником.

<a name="business_opportunities"/>

### 1.2.2 Возможности бизнеса
Проект по записи и редактированию личных заметок предлагает множество возможностей. Во-первых, возможность легко и просто организовывать личные заметки. Во-вторых, управление записями и возможность корректирования собственных планов.

<a name="project_boundary"/>

### 1.2.3 Границы проекта
Приложениене будет включать функции для управления проектами или задачами на уровне команды и не будет включать встроенные инструменты для анализа данных или создания отчетов.

<a name="analogues"/>

## 1.3 Аналоги
Аналогами являются такие приложения как Microsoft OneNote, Google Keep, Bear.

<a name="user_requirements"/>

# 2 Требования пользователя

<a name="software_interfaces"/>

## 2.1 Программные интерфейсы
Продукт будет взаимодействовать с несколькими внешними системами:

•	Firebase Authentication для авторизации и хранения данных пользователей.

•	Note Database для локального хранения заметок.


<a name="user_interface"/>

## 2.2 Интерфейс пользователя
Окно загрузки приложения.  

![Окно загрузки приложения](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/Loading.png)  

Окно регистрации нового пользователя.  

![Окно регистрации нового пользователя](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/Registration.png)

Окно входа для зарегистрированного пользователя.  

![Окно входа для зарегистрированного пользователя](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/Sing.png)

Главное окно приложения.

![Главное окно приложения](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/Note%20List.png)

Окно создания новой заметки. 

![Окно создания новой заметки](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/NoteSpace.png) 

Окно избранное. 

![Окно избранное](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/Favorites.png)

Окно поиска. 

![Окно поиска](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/Search.png) 

Меню. 

![Меню](https://github.com/ElenaLeibuk/Personal-Notes/blob/master/mockups/Menu.png) 

<a name="user_specifications"></a>
### **2.3 Характеристики пользователей:**

Пользователи - люди, стремящиеся к упорядоченности и эффективности в своей повседневной жизни. Уровень опыта - разный. Возрастная группа различается от молодых пользователей до пенсионеров, т.е. пользователи с базовыми навыками работы с мобильными приложениями, которые ценят простоту и удобство в использовании. Они ищут инструмент, который поможет им легко создавать, редактировать и организовывать свои заметки без лишних сложностей.

<a name="assumptions_and_dependencies"></a>
### **2.4 Предположения и зависимости:**

•	Не обязательно иметь связь с интернетом, чтобы создать и отредактировать личные заметки.

•	Приложение будет работать только на устройствах с Android 6.0 и выше.

<a name="system_requirements"></a>
## **3. Системные требования**

<a name="functional_requirements"></a>
### **3.1 Функциональные требования:**

• Приложение должно позволять пользователям добавлять, редактировать, просматривать и удалять личные заметки.
	
•	Приложение должны быть избранные заметки для удобства пользования.
	
•	Авторизация необходима для конфиденциальности личнх записей.
   
•	Приложение должно поддерживать синхронизацию данных с облаком (Firebase).

<a name="non-functional_requirements"></a>
### **3.2 Нефункциональные требования:**

•	Надёжность: Приложение должно быть устойчивым к потерям соединения с интернетом, с возможностью локального хранения данных и последующей синхронизации.

•	Безопасность: Данные пользователей должны быть защищены, а авторизация — проводиться через надёжную систему (например, Firebase Authentication).

•	Производительность: Приложение должно загружаться и работать плавно на большинстве современных устройств.

•	Удобство использования: Интерфейс должен быть интуитивно понятным, особенно для пользователей с базовыми техническими навыками.
