# 1. Общие положения

##1.1 Полное наименование системы и ее условное обозначение

1.1.1. Информационная система автоматизации перевода и легализации паспортов.

##1.2. Наименование организаций заказчика и разработчика

1.2.1. Заказчик ООО "Линкс Динамикс".

1.2.2. Разработчик ФГАОУ ВО «ПНИПУ».

##1.3. Порядок оформления и предоставления заказчику результатов работ

Система передается в виде функционирующего комплекса на базе средств вычислительной техники Заказчика. Работы принимаются комиссией, состоящей из представителей Заказчика и Исполнителя.

#2. Назначения и цели создания системы
##2.1.  Назначение

Система предназначена для обработки информации из документов удостверяющих личность граждан.

##2.2. Цели и задачи создания системы

Система создаётся с целью получения инструмента обработки информации для отдела перевода предприятия Заказчика.

В результате создания Системы должны быть решены следующие задачи:

1. ввод данных документа удостверяющего личность;
2. вывод отсканированного документа удостверяющего личность;
3. интеграция с Системой распознавания текстов;
4. совместный доступ к данным документа удостоверяющего личность.

#3. Характеристика объекта автоматизации

Объектом автоматизации является процесс получения легализированного документа удостверяющего личность гражданина.

#4. Требования к системе

##4.1. Требования к системе в целом

###4.1.1. Требования к структуре и функционированию системы

####4.1.1.1 Алгоритм работы пользователя системы

Конечный пользователь системы обязан следовать следующему алгоритму работы с системой:

0. регистрация пользователя в Системе
1. аутентификация пользователя в Система
2. работа в Системе

2.1. загрузка в в систему новых данных
2.1.1.
2.1.2.

2.2 работа с загруженными данными пользователя 
2.2.1. 
2.2.2. 
3. выход из системы

####4.1.1.2 Перечень подсистем, их назначение и основные характеристики

В Системе предполагается выделить следующие функциональные модули:
1. модуль веб-приложения для работы с пользователями системы;
2. модуль загрузки данных из отсканированных паспортов;

####4.1.1.3 Требования к способам и средствам связи для информационного обмена между компонентами системы

Подсистемы в процессе функционирования должны осуществлять обмен информацией на основе открытых форматов обмена данными, используя для этого входящие в их состав модули информационного взаимодействия.

####4.1.1.4 Требования к характеристикам взаимосвязей создаваемой системы со смежными системами

Система должна осуществлять обмен информацией со смежными системами по локальной сети. В рабочем состоянии Система должна иметь доступ к сети интернет.

####4.1.1.5 Требования к режимам функционирования системы

Предусмотрено использование Системы в следующих режимах:
1. режим первоначального заполнения данными;
2. основной режим;
3. аварийный режим;

####4.1.1.6 Требования по диагностированию системы

Диагностика и профилактика технических средств, проводится провайдером информационных услуг по мере необходимости.

####4.1.1.7 Перспективы развития, модернизации системы

Система должна иметь возможность дальнейшей модернизации программного обеспечения.

###4.1.2. Требования к квалификации и численности персонала

В состав персонала необходимо выделение следующих ответственных лиц:
1. переводчик;
2. администратор системы;
3. остальные пользователи системы;

К квалификации персонала, эксплуатирующего Систему, предъявляются следующие требования: персонал системы должен обладать навыками уверенного пользователя ПК.

###4.1.3. Показатели назначения

Система должна одновременно обслуживать до 100 пользователей.

###4.1.4. Требования к безопасности

Требования не предъявляются.

###4.1.5. Требования к эргономике и технической эстетике

Система должна обеспечивать доступ к тексту оригинала и к форме с переводом.

###4.1.6. Требования к эксплуатации, техническому обслуживанию, ремонту и хранению компонентов системы

Требования не предъявляются.

###4.1.7. Требования к сохранности информации при авариях

Программное обеспечение Системы должно восстанавливать свое функционирование при корректном перезапуске аппаратных средств.

###4.1.8. Требования к защите от влияния внешних воздействий

Оборудование и ПО должны быть защищены от внешних воздействий в полном соответствии с требованиями по эксплуатации.

###4.1.9. Требования к патентной чистоте

Требования не предъявляются.

##4.2. Требования к функциям, выполняемым системой

В Системе должны быть реализованы следующие функции:

1. загрузка сканированного докуманта удостверяющего личность;
2. сохранение полученного результата;
3. выдача полученного результата в формате "docx".

Система должна обеспечивать выполнение функций обработки документов:

1. ручная обработка оператором (перевод, исправление ошибок);
2. автоматический переход от сканированного докуманта в формат обработки;
3. сохранение изменений.

##4.3. Требования к видам обеспечения

###4.3.1. Требования к математическому обеспечению

Математическое обеспечение должно обеспечивать в системе реализацию перечисленных в ТЗ функций и требований. Используемые алгоритмы должны соответствовать требованиям быстродействия и безопасности фреймворка Django / Flask.

###4.3.2. Требования к лингвистическому обеспечению

Все программное обеспечение Системы для организации взаимодействия с пользователем использует русский язык, а также иметь возможность работы со всеми языками, утверждёнными в перечне стран-носителей.

###4.3.3. Требования к программному обеспечению системы

При проектировании, разработке и эксплуатации Системы следует использовать следующее программное обеспечение:
1. язык программирования Python 3;
2. фреймворк на языке программирования Python для разработки веб-приложений
3. Django;
4. СУБД MongoDB.
5. ABBYY FineReader Engine

###4.3.4. Требования к техническому обеспечению

Требования не предъявляются.

###4.3.5. Требования к организационному обеспечению

Требования не предъявляются.

###4.3.6. Требования к методическому обеспечению

Требования не предъявляются.

#5. Состав и содержание работ по разработке системы

Основные этапы создания Системы.

1. Исследовательская часть:
1.1 Обзор существующих решений.

2. Технологическая часть.
2.1. "Разработка модели пользователя приложения, механизма регистрации
пользователей, механизма входа-выхода из приложения (серверная часть)."
2.2. "Разработка интерфейса формы регистрации пользователей, и
входа-выхода из приложения (клиентская часть)."
2.3. Тестирование работы разработанного интерфейса.
2.4. Разработка модели данных совместно с описанием структуры форм для
заполнения.
2.5. Разработка модуля генерации ссылок на документы.
2.6. Разработка модуля поиска по критериям документов.
2.7. Обеспечение обмена данными с клиентом (прием, отправка и разбор
данных, серверная часть).
2.8. Тестирование полученной серверной части.
2.9. Выполнение тестирования взаимодействия компонентов системы.
2.10. Развертывание системы:
2.10.1. Настройка сервера приложений;
2.10.2. Настройка веб-сервера;
2.10.3. Настройка сервера СУБД;
2.10.4. Настройка DNS и доменных имён.

3. Техническое задание.
3.1. Написание технического задания.
3.2. Согласование технического задания с Заказчиком.

#6. Порядок контроля и приемки системы

##6.1. Объем, виды, состав и методы испытаний системы

Предварительные испытания проводятся Разработчиком на тестовых данных на соответствие заявленным функциям Системы.

##6.2. Общие требования к приемке работ по стадиям

Все работы по приемке Системы осуществляются комиссией, состоящей из представителей Заказчика и Разработчика.

#7. Требования к составу и содержанию работ по подготовке объекта автоматизации к вводу системы в действие

Перед вводом Системы в эксплуатацию Заказчик обязан обеспечить проведение следующих работ:

1. определить должностных лиц и подразделение, ответственных за внедрение и проведение опытной эксплуатации Системы;
2. обеспечить програмно-технические средства, на которых будет установлена Система; 
3. организовать и провести опытную эксплуатацию Системы.

#8. Требования к документации

Требования не предъявляются.

#9. Источники разработки

Данное техническое задание разработано при использовании следующих
документов:
ГОСТ 34.602.-89 «Техническое задание на создание автоматизированной системы»
Составили
Наименование организации, предприятия
Должность исполнителя
Фамилия, имя, отчество
Подпись
Дата
ПНИПУ
Главный разработчик
Ларионов А.А.


Согласовано
Наименование организации, предприятия
Должность исполнителя
Фамилия, имя, отчество
Подпись
Дата
ПНИПУ
