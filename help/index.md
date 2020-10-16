---
title: DomoMeter / Справка
description: Справка по приложению DomoMeter
topic: help
---

<ol class="breadcrumb pull-right">
  <li><a href="/">DomoMeter</a></li>
  <li class="active">Справка</li>
</ol>

# Справка

Перед тем, как начать пользоваться программой, необходимо выполнить несколько простых действий по настройке.  
Если у вас возникают трудности при пользовании программой, то вы всегда можете обратиться к данному разделу помощи.  

<ul id="tabs-help" class="nav nav-tabs" role="tablist">
<li role="presentation" class="active"><a href="#by-steps" aria-controls="by-steps" role="tab" data-toggle="tab">По шагам</a></li>
<li role="presentation"><a href="#by-topics" aria-controls="by-steps" role="tab" data-toggle="tab">По разделам</a></li>
</ul>

<div class="tab-content">
<div role="tabpanel" class="tab-pane active fade in" id="by-steps" markdown="1">

Ниже даны ссылки на разделы помощи в том порядке, в котором они могут вам пригодиться.  
Если не знаете с чего начать, начните с самого первого пункта.

* Создайте [счётчики](/help/counters) в соответствии с приборами учёта, установленными у вас дома. При создании счётчиков укажите [тарифы](/help/tariffs), которые будут использоваться по умолчанию.  

* Создайте необходимое число [услуг](/help/services) (источников платежей без счётчиков). При создании услуг также укажите [тарифы](/help/tariffs), которые будут использоваться по умолчанию.  

* Для сложных вариантов начисления стоимости услуг используйте способ расчёта [по формуле](/help/formula).  

* Откройте [журнал показаний](/help/journal). Добавьте новый месяц.  

* [Введите показания](/help/readings) для только что добавленного месяца для тех счётчиков, для которых это необходимо. В детальной статистике по месяцу отобразятся все статьи расходов.

* Укажите [разовые услуги](/help/singles), если они есть для данного месяца.

* Если вы хотите отслеживать реальные платежи, с учётом задолженностей или переплат, создайте [счёт](/help/bills) и укажите счётчики и услуги, которые в него включены.

* Если нужно, отправьте показания по [Email](/help/send-email) или [SMS](/help/send-sms) в принимающую организацию, либо [распечатайте показания](/help/printing) на принтере.

* Если есть необходимость, можно сделать [экспорт показаний](/help/export) в CSV файл.

* Чтобы не забыть, когда нужно снимать показания и оплачивать счета, воспользуйтесь [напоминаниями](/help/reminders).

* Если беспокоитесь, что потеряете данные, лучше сделать [резервную копию](/help/backup).

* Если требуется вернуть либо загрузить данные с другого устройства, воспользуйтесь [восстановлением данных](/help/restore).

* Если у вас есть дача, где также нужно вести учёт коммунальных услуг, или другая квартира или дом, создайте [дополнительную квартиру](/help/houses) и повторите указанные операции для нового объекта жилья.

</div>
    <div role="tabpanel" class="tab-pane fade" id="by-topics" markdown="1">

### Начало работы
  * [Главный экран](/help/mainscreen)
  * [Счётчики](/help/counters)
  * [Услуги](/help/services)
  * [Тарифы](/help/tariffs)
  * [Расчёт услуг по формуле](/help/formula)
  * [Счета](/help/bills)
  * [Квартиры](/help/houses)
  * [Напоминания](/help/reminders)
  
### Журнал
  * [Добавление месяца](/help/journal)
  * [Месяц: счётчики и услуги](/help/readings)
  * [Месяц: платежи](/help/payments)
  * [Разовые услуги](/help/singles)
  
### Операции
  * [Отправка показаний в SMS](/help/send-sms)
  * [Отправка показаний в EMail](/help/send-email)
  * [Отправка показаний на печать](/help/printing)
  * [Экспорт показаний](/help/export)
  * [Генерация QR-кода для оплаты](/help/qrcode)
   
### Шаблоны
  * [Шаблоны SMS](/help/sms-templates)
  * [Шаблоны EMail](/help/email-templates)
  * [Шаблоны печати](/help/printing-templates)
  * [Теги](/help/tags)
 
### Графики
  * [График расходов](/help/charts-expenses-history)
  * [Диаграмма расходов](/help/charts-expenses-monthly)
  * [График потребления](/help/charts-consumption)
  * [График тарифов](/help/charts-tariffs)
  * [График платежей](/help/charts-payments) 
 
### Резервная копия и восстановление
  * [Создание резервной копии данных](/help/backup)
  * [Восстановление из резервной копии](/help/restore)
  
### Прочее
  * [Интеграция с Saures](/help/saures)
  * [Виджет](/help/widget)
  * [Настройки](/help/settings)
  
</div>
</div>

<br><br>

<script type="text/javascript">
	$(document).ready(function() {
		$('a[data-toggle="tab"]').on('show.bs.tab', function(e) {
			localStorage.setItem('activeTab', $(e.target).attr('href'));
		});
		var activeTab = localStorage.getItem('activeTab');
		if (activeTab) {
		   $('#tabs-help a[href="' + activeTab + '"]').tab('show');
		}
	});
</script>