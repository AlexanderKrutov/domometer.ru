--- 
Title: DomoMeter / История версий 
Description: История версий 
topic: versions
--- 
 
# Различия версий DomoMeter и DomoMeter Lite 
 
Обе версии программы одинаковы по функционалу, но Lite версия имеет ограничение на количество счётчиков и услуг.  
  
Если у вас дома один или два счётчика — вам подойдёт бесплатная версия.   
Если больше — вам нужна полная версия. Её можно скачать в Google Play всего за {{site.price}} рублей.   
 
|                                   | DomoMeter Lite  | DomoMeter         | 
| --------------------------------- |:---------------:|:-----------------:| 
| Максимальное количество счётчиков | 2               | без ограничений   | 
| Максимальное количество услуг     | 2               | без ограничений   | 
| Цена                              | [бесплатно][1]  | [{{site.price}} руб.][2] | 
 
[1]: https://play.google.com/store/apps/details?id=org.krutov.domometer.lite 
[2]: https://play.google.com/store/apps/details?id=org.krutov.domometer 
 
# История версий 
 
Ссылка в номере ведёт на страницу анонса версии на форуме. 

### [3.7](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=68629826) <sup class="text-muted"><small>29 декабря 2017<small>
* Интеграция с личным кабинетом системы Saures
* Исправлена ошибка неверной обработки тегов в формулах для многотарифных счётчиков
* Исправлено: не отображается предыдущий расход для услуг в графике потребления
* Изменено представление графика расходов

### [3.6.4](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=67262278) <sup class="text-muted"><small>20 ноября 2017<small>
* Исправлена проблема с невозможностью сохранить резервную копию по расписанию в произвольную локальную папку

### [3.6.3](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=67220926) <sup class="text-muted"><small>19 ноября 2017<small>
* Улучшена работа резервной копии по расписанию (используется новый планировщик задач)
* Исправлено: не меняется счётчик или услуга в некоторых графиках
* Исправлено: файл резервной копии недоступен для выбора
* Добавлены недостающие строки в локализации

### [3.6.2](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=66639632) <sup class="text-muted"><small>03 ноября 2017<small>
* Теперь можно запомнить выбранное приложение для отправки сообщений и почты
* Диалог выбора квартиры теперь не содержит кнопки подтверждения
* Исправлена проблема с невозможностью прикрепить квитанцию в \*.jpg (доступно только \*.pdf) для не стоковых файловых браузеров
* Исправлена проблема с плохим качеством изображений квитанций в списке
* Исправлено: не меняется счётчик или услуга в графике потребления

### [3.6.1](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=66364319) <sup class="text-muted"><small>26 октября 2017<small>
* Исправлена проблема с неработающей отправкой сообщений и писем на Marshmallow+
* Исправлена неверная кодировка при считывании QR-кода

### [3.6](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=66286991) <sup class="text-muted"><small>23 октября 2017<small>
* Возможность добавлять квитанции в PDF
* Возможность отправить показания счётчиков через мессенджеры
* В списках счётчиков, услуг, счетов, тарифов добавлены фильтры
* Смена квартиры по долгому нажатию на заголовок окна
* Улучшения в работе напоминаний
* Исправлена ошибка с округлением в формулах
* Исправления других ошибок

### [3.5.1](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=65396564) <sup class="text-muted"><small>26 сентября 2017<small>
* Исправлена ошибка с обновлением базы данных (проявлялась только у тех, кто обновляется со старых версий баз, до 3.0)
* Изменён алгоритм группировки расходов с информации о платеже. Теперь группировка по имени группы не учитывает тип счётчика или услуги
* Изменён диалог детальной информации о группе расходов — теперь там показываются иконки входящих в группу счётчиков и услуг.

### [3.5](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=65218297) <sup class="text-muted"><small>20 сентября 2017<small>
* Исправлена проблема с округлением сумм в журнале
* Исправлена проблема с некорректным расчётом сумм при использовании тарифа с общим порогом
* Возможность группировки статей расходов в платежах по счетам
* Изменения в настройках отправки Email и печати (выбор и сортировка значений и счётчиков)
* Резервное копирование по расписанию в локальную папку: права на доступ теперь удерживаются

### [3.4](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=62708173) <sup class="text-muted"><small>26 июня 2017<small>
* Возможность указать формулу для расчёта услуги
* Добавлен перевод на белорусский язык
* Норма расхода тепловой энергии теперь вынесена в свойства услуги
* Добавлена кнопка «Не указывать» в диалог выбора даты
* Исправлена ошибка с неверной кодировкой при считывании реквизитов счёта из QR-кода
* Исправлена ошибка при вставке тарифа в истории тарифов
* Исправлена проблема с незапланированным показом напоминаний 10 числа
* Исправлена проблема с невозможностью ввода отрицательных сумм на Samsung
* Другие мелкие улучшения

### [3.3](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=62017642) <sup class="text-muted"><small>02 июня 2017<small> 
* Общий (пропорциональный) порог для многотарифного счётчика
* Считывание реквизитов счёта из QR-кода в квитанции
* Операции «Копировать» и «Вставить» в истории тарифов
* Исправлена проблема с повторяющимися напоминаниями в конце месяца
* Исправления ошибок и другие мелкие улучшения

### [3.2](http://4pda.ru/forum/index.php?showtopic=422857&view=findpost&p=61857465) <sup class="text-muted"><small>28 мая 2017<small> 
* Температурный коэффициент для газового счётчика
* Норма расхода тепловой энергии для услуг с типами «Отопление» и «Подогрев горячей воды»
* Суточная норма потребления внутри тарифа
* Услуги с типами «Холодная вода» и «Горячая вода» теперь могут иметь способ расчёта «Суммарный расход»
* Число десятичных знаков в счётчиках увеличено до 5
* Дополнительная настройка резервной копии по расписанию: раз в день, если были изменения данных
* Добавлена настройка «Стартовый экран»
* Исправлена проблема с неработающими напоминаниями на некоторых устройствах

### [3.1](http://4pda.ru/forum/index.php?showtopic=422857&view=findpost&p=61548766) <sup class="text-muted"><small>19 мая 2017<small> 
* Резервная копия по расписанию в папку на устройстве и в облачные хранилища (Google Drive, Dropbox)
* Исправлен алгоритм работы с системным проводником файлов
* Исправлена ошибка, при которой на некоторых устройствах не отображались почтовые клиенты в отправке показаний по электронной почте
* При сохранении изменённого шаблона теперь автоматически подставляется его имя
* Сохранение реквизитов счёта без обязательных параметров
* Перевод на украинский язык

### [3.0.2](http://4pda.ru/forum/index.php?showtopic=422857&view=findpost&p=60474264) <sup class="text-muted"><small>15 апреля 2017<small> 
* Порог и льготы верно вычисляются для услуг с типом расчёта «Площадь» и «Количество жильцов»
* Теперь для услуг с фиксированной суммой валюта отображается верно
* Слегка изменены цвета на графиках, чтобы их удобнее было различать
* В стандартном проводнике документов DocumentsUI SD-карта отображается по-умолчанию
* Текст на вводном экране больше не обрезается
* Исправлено некорректное отображение отсутствующего показания счётчика на старых версиях Android
* Если включена настройка «Крупный текст», надписи масштабируются корректно
 
### [3.0.1](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=60231395) <sup class="text-muted"><small>08 апреля 2017<small> 
Исправления ошибок:
* Не работает перевод единиц измерения в счётчике отопления и коэффициент трансформации для счётчика электроэнергии.
* Падение при открытии стандартного браузера документов на некоторых устройствах (ActivityNotFoundException).
* Длинное имя счётчика не помещается на карточке показаний.

### [3.0](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=60215726) <sup class="text-muted"><small>07 апреля 2017<small> 
* Полностью переработанный интерфейс в стиле Material Design 
* Генерация QR-кода для оплаты через платёжный терминал 
* Теперь в параметрах счетов и платежей указываются счётчики и услуги, а не категории расходов 
* Улучшено взаимодействие с хранилищами данных (SAF) 
* Запрос разрешений в процессе работы (Runtime Permissions) 
* Новые переработанные графики 
* Подсказки для всех элементов 
* Прочие улучшения функционала 
 
### [2.3](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=35782467) <sup class="text-muted"><small>15 ноября 2014<small> 
+ Выбор номера из телефонной книги при отправке SMS 
+ Поддержка отрицательного расхода для счётчиков 
* Исправлена ошибка с крешем полной версии приложения на Android 5.0 Lollipop 

### [2.2](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=35556609) <sup class="text-muted"><small>07 ноября 2014<small> 
+ Добавлен виджет  
+ Меню истории тарифов и истории показаний 
* Исправлена ошибка с отсутствующим номером лицевого счета 
* Исправлена ошибка с неучётом пени для предыдущих месяцев 
 
### [2.1](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=33995944) <sup class="text-muted"><small>03 сентября 2014<small> 
+ Фотографии квитанций для счетов 
+ Полная резервная копия, включая файлы квитанций  
+ Кнопка «Оплачено» в окне ввода суммы платежа 
+ В режиме калькулятора для счётчиков отображается сумма, а не показание 
* Исправлена ошибка с восстановлением базы данных из резервной копии 
* Исправлена некорректная индикация оплаченных счетов 
* Исправлен неработающий тег «Сегодня» 
* Кнопка «Назад» в окне «Информация» теперь работает 
 
### [2.0](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=33275094) <sup class="text-muted"><small>01 августа 2014<small> 
+ Учет сумм фактической оплаты: счета и платежи 
+ Новый способ расчёта услуг — «Количество дней» 
+ Неактивные счётчики и услуги выделяются специальным значком  
* Исправлено: ошибка с округлением в меньшую сторону 
* Исправлено: вспышка не тухнет при голосовом вводе 
* Исправлена ошибка при отправке показаний 
* Исправлена ошибка с дубликатами напоминаний 
* Исправлена ошибка с расчётом водоотведения 
* Улучшения в интерфейсе 
 
### [1.13](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=28963127) <sup class="text-muted"><small>31 января 2014<small> 
* Голосовой ввод показаний счётчиков 
* Новые типы услуг: «Содержание системы ГВС» и «Электроэнергия» 
* Новый способ расчёта услуг: «Количество жильцов» 
* Добавлен тег для даты снятия показания счётчика 
* Перевод единиц измерения для счётчика отопления 
* Коэффициент трансформации для электросчётчика 
* Исправления ошибок и улучшения в интерфейсе 
 
### [1.12](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=26921037) <sup class="text-muted"><small>23 ноября 2013<small> 
* Поддержка Android 4.4 
* Общая сумма на графике платежей 
* Исправлено правило показа напоминаний в конце месяца 
* Исправления ошибок 
 
### [1.11](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=26158779) <sup class="text-muted"><small>27 октября 2013<small> 
* Печать таблицы показаний с помощью Cloud Printer 
* Сортировка списка счётчиков 
* Выбор тарифа из уже существующих 
* Подробная информация о расходе и сумме к оплате 
* Исправления ошибок 
 
### 1.10.2 <sup class="text-muted"><small>30 сентября 2013<small> 
* Исправления ошибок 
 
### 1.10.1 <sup class="text-muted"><small>28 сентября 2013<small> 
* Исправления ошибок 
 
### [1.10](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=25381216) <sup class="text-muted"><small>27 сентября 2013<small> 
* Любое число напоминаний и отложенные напоминания 
* Срок действия счётчиков и услуг 
* Калькулятор сумм в Журнале за месяц 
* Поддержка казахского языка 
* Исправления ошибок 
 
### 1.9.1 <sup class="text-muted"><small>27 августа 2013<small> 
* Добавлены теги для многотарифных счётчиков 
 
### [1.9](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=24568765) <sup class="text-muted"><small>26 августа 2013<small> 
* Отправка показаний с помощью SMS 
* Шаблоны SMS 
* Шаблоны EMail 
* Возможность указывать дробные значения процентов в льготах 
* Исправления ошибок 
 
### [1.8](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=23124652) <sup class="text-muted"><small>28 июня 2013<small> 
* Расширенный тип тарификации для услуг 
* Отправка показаний на EMail в виде простого текста 
* Примечания к показаниям 
* Поле "адрес" для квартир 
* Сохранение пути для резервного копирования 
* Исправлена ошибка отображения графиков при смене ориентации экрана 
* Добавлены подсказки для кнопок на actionbar 
 
### [1.7](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=21612098) <sup class="text-muted"><small>28 апреля 2013<small> 
* Новые типы услуг 
* График изменения тарифов 
* До 5 десятичных знаков в значениях расхода, норматива, площади 
* Исправлена валидация EMail адреса 
* Исправлено выключение фонарика при повороте экрана 
 
### 1.6.1 <sup class="text-muted"><small>09 апреля 2013<small> 
* Исправлена ошибка с некорректным отображением actionbar кнопок на планшетах и телефонах с большим разрешением 
 
### [1.6](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=21122693) <sup class="text-muted"><small>08 апреля 2013<small> 
* Поддержка нескольких квартир 
* Стилизация интерфейса (ActionBar) 
* Категории в настройках счётчика или услуги 
* Асинхронное выполнение трудоёмких операций 
* Исправления ошибок 
 
### [1.5](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=20322645) <sup class="text-muted"><small>12 марта 2013<small> 
* Поддержка сложных тарифов (с двумя порогами, с льготой в процентах) 
* Разовые платежи 
* Ввод даты показаний 
* Возможность менять норматив или площадь услуги в выбранном месяце 
* Услуги "домофон" и "антенна" 
* Исправления ошибок 
 
### 1.4.2 <sup class="text-muted"><small>18 февраля 2013<small> 
* Возможность удалять показание счётчика 
* Исправлена ошибка в детальной статистике месяца при отсутствующих показаниях 
* Исправлены ошибки в украинской локализации 
 
### 1.4.1 <sup class="text-muted"><small>17 февраля 2013<small> 
* Возможность сохранять программу на SD карту 
* Значение тарифных ставок теперь может иметь до четырёх десятичных знаков 
* Исправлена ошибка при вводе дробных значений норматива или площади 
 
### [1.4](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=19575179) <sup class="text-muted"><small>14 февраля 2013<small> 
* Локализация на украинский и белорусский языки 
* Услуга "подогрев горячей воды" 
* Резервная копия и восстановление данных из файла 
* Ввод суммы перерасчёта 
* Произвольный текст для напоминания 
* Напоминания в разные дни месяца 
* Исправлена ошибка с неработающим фонариком на устройствах с Android 4.0+ 
* Исправлена ошибка с напоминанием, возникающим при отключённых настройках 
* Изменён тип клавиатуры при вводе начальных показаний счётчиков 
* Элементы интерфейса с возможностью редактирования сделаны кликабельными 
 
### [1.3](http://4pda.ru/forum/index.php?s=&showtopic=422857&view=findpost&p=19189810) <sup class="text-muted"><small>01 февраля 2013<small> 
* Добавлена отправка показаний счётчиков по электронной почте 
* Добавлен экспорт показаний в файл формата CSV (может быть открыт в Excel) 
* Добавлены подсказки к некоторым элементам 
* Добавлен диалог выбора месяца перед открытием страницы показаний 
* Исправления ошибок 
 
### 1.2 <sup class="text-muted"><small>11 января 2013<small> 
* Добавлены источники платежей без счётчиков (услуги) 
* Добавлена детальная статистика расходов по месяцам 
* Добавлено начальное значение счётчика 
* Водоотведение перенесено в услуги 
* Настройки временно перенесены в меню 
* Исправления ошибок 
 
### 1.1 <sup class="text-muted"><small>22 декабря 2012<small> 
* Добавлен счётчик водоотведения 
* Добавлен диалог истории версий 
* Изменён дизайн иконок счётчиков 
* Изменение разрешений доступа к вспышке камеры (теперь программа доступна на большем числе устройств) 
* Исправления ошибок 
 
### 1.0.1 <sup class="text-muted"><small>07 декабря 2012<small> 
* Исправлена ошибка, при которой не удалялись показания при удалении счётчика 
* Исправлена ошибка, когда при развёрнутом списке показаний на месяц при редактировании тарифа открывался неверный тариф 
* Исправлена ошибка, при которой появлялось необработанное исключение при открытии контекстного меню для последнего элемента в списке показаний на месяц 
* Исправлена ошибка, при которой для нового месяца при отсутствии введённых показаний отображался неверный расход счётчика 
 
### 1.0 <sup class="text-muted"><small>01 декабря 2012<small> 
* Первая версия программы 
 
<br>