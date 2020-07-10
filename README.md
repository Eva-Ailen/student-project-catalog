# student-project-catalog
<h1> Коллекция студенческих проектов </h1>
В каталоге представлены "хорошие" программные проекты, выполненные в ходе лабораторных работ
с использованием технологии JavaFX

## Содержание
- Функциональность
  - [Калькулятор энергопотребления](#калькулятор)
  - [Редактор CSS-стилей](#редактор)
  - [Сборщик файлов](#сборщик)
  - [Моделирование пожарной сигнализации](#сигнализация)
  - [Метеостанция](#Метеостанция)
  - [Модуль авторизации](#versioning)
  - [Хранилище личных достижений](#basedata)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
- Техники
  - [Автогенерация полей](##Калькулятор)
  - [unit-тесты](#Сигнализация)
  - [смена сцен](#Редактор)
- Паттерны
  - [Абстрактная фабрика]((#Калькулятор)
  - [unit-тесты](#Сигнализация)
  - [смена сцен](#Редактор)
- Архитектуруы
  - [Событийно-управляемая архитектура]((#Калькулятор)
  - [unit-тесты](#Сигнализация)   
    
## Калькулятор
 [Калькулятор энергопотребления](https://github.com/range36rus/power_calculate.git)
  Предназначен для расчета суммарного энергопотребления различных устройств
  GUI позволяет вводить/изменять значения потребляемой мощности, часов работы
  Файл настроек содержит значения потребляемой мощности, используемые по умолчанию
### Используемые методы и технологии программирования
  1. Автогенерация полей GUI на основе данных в текстовом файле
  2. Использование паттерна Абстрактная фабрика для вывода значений из файла как в виде текстовго поля, так в виде списка

## Редактор
  <h2>[Редактор CSS-стилей](https://github.com/range36rus/cssfx-style-editor.git)</h2>
    Предназначен для редктирования css-стилей для fxml-форм
    Изменения внесенные в css в текстовом редакторе, оперативно отображаюся в окне пользовательского интерфейса
### Используемые методы и технологии программирования
 <li>
  1. Смена сцен 
  2. Использование 
  3. 
  </li>  

## Сборщик
 <h2>[Сборщик файлов](https://github.com/vladder2312/JavaCollector.git)</h2>
    Предназначен для создания листинга программного проекта
    Из заданного каталога выбирает классы java в один общий файл
### Используемые методы и технологии программирования
  <li>
  1. Использование стандартных диалогов
  2. Паттерн Итератор для прохода по каталогу
  </li>

## Сигнализация 
 <h2>[Сборщик файлов](https://github.com/vladder2312/AlarmSystem.git)</h2>
    Предназначен для моделирования работы системы пожарной сигнализации
    используется событийное управление
### Используемые методы и технологии программирования
  <li>
  1. Случайная генерация событий по таймеру
  2. Паттерн Цепочка обязанностей для обработки различных событий
  3. Unit-тесты
  </li>  

## Метеостанция
  <h2>[Сервер метеонаблюдения](https://github.com/RinaKoner128/ClientServer.git)</h2>
    Предназначен для сбора данных о температуре воздуха в разных населенных пунктах
    Клиенты передают значения температуры в своем населенном пункте Серверу
    могут запросить с Сервера температуру по названию города
### Используемые методы и технологии программирования
  <li>
  1. Клиент-серверная архитекутра с простым протоколом
  2. Использование Map для хранения неповторяющихся данных на Сервере
  </li>  
 
## versioning
  <h2>[Модуль авторизации](https://github.com/RinaKoner128/ClientServer.git)</h2>
    Предназначен для переключения режима работы в зависимости от вида пользователя
### Используемые методы и технологии программирования
  <li>
  1. Оформление проекта
  2. Паттерн Медиатор
  </li> 

## basedata
  <h2>[Хранилище личных достижений](https://github.com/AndreevaKristina99/DataBase.git)</h2>
    Предназначен для хранения личных достижений в виде описания и изображения
### Используемые методы и технологии программирования
  <li>
  1. Работа с email
  2. Вывод в таблицу
  3. Паттерн ADO
  </li>  
  
