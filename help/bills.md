---
title: DomoMeter / Справка / Счета
description: Справка по приложению DomoMeter — «Счета»
topic: help
video: bills
---

<div class="row">
<ol class="breadcrumb pull-right">
  <li><a href="/">DomoMeter</a></li>
  <li><a href="/help">Справка</a></li>
  <li class="active">Счета</li>
</ol>
</div>

<script type="text/javascript">
	var screenshots = [
	  '/assets/img/screens/bills.png', 
	  '/assets/img/screens/bill-properties.png',
	  '/assets/img/screens/bill-details.png'
	];
</script>
{% include_relative _screenshot.md %}

<div class="instruction" markdown="1">

# Счета

Счета необходимы для контроля реально оплаченных сумм с учётом переплат, задолженностей, перерасчётов и пени.  

Термин «счёт» в программе DomoMeter соответствует вашему лицевому счёту в организации, предоставляющей жилищно-коммунальные услуги.

## Создание и редактирование счёта

* Находясь на главном экране программы, откройте боковое меню и выберите раздел «Счета». 
 
* Для создания нового счёта нажмите на «Плюс» в правом нижнем углу, для редактирования выберите нужный счёт в списке. 
 
* В открывшемся окне укажите основные свойства счёта: 
  * *Название* — должно быть уникальным для каждого счёта. 
  * *Начальная сумма* — начальная сумма на счёте. Может быть нулевой.
  * *Счётчики и услуги* — список [счётчиков](/help/counters) и [услуг](/help/services), включённых в счёт. 
  * *Группировка счётчиков и услуг* — то, каким образом следует группировать счётчики и услуги в детальной информации о [платеже по счёту](/help/payments). 
  
* *Реквизиты счёта*. 
Реквизиты нужны для того, чтобы автоматически создавать [QR-код для оплаты](/help/qrcode) через платёжный терминал. 
Значения реквизитов счёта можно узнать из платёжной квитанции: ввести вручную или сканировать QR-код, если он напечатан на документе.

  **Обязательные реквизиты:**
  
  * *Получатель платежа* — название получателя платежа; как правило, это наименование управляющей организации, ТСЖ или ДУКа;
  * *Банк получателя платежа* — наименование банка, в котором открыт счёт для перечисления средств;
  * *БИК банка* — код БИК для банка получателя (9 цифр);
  * *Кор. счёт банка* — корреспондентский счёт банка получателя (20 цифр);
  * *Номер счёта получателя* — номер счёта управляющей организации (ТСЖ, ДУКа) в банке получателя (20 цифр);
  
  Без указания обязательных реквизитов [создание QR-кода для оплаты](/help/qrcode) невозможно.
  
  **Дополнительные реквизиты:**
  
  * *ИНН получателя* — ИНН (индивидуальный налоговый номер) получателя платежа;
  * *КПП получателя* — КПП (код причины постановки на учёт) получателя платежа;
  * *Номер лицевого счёта плательщика* — индивидуальный номер счёта плательщика в принимающей организации. Обратите внимание, что этот номер не совпадает с номером счёта получателя. 
  * *Фамилия плательщика*;
  * *Имя плательщика*;
  * *отчество плательщика*;
  
  Реквизиты счёта также могут быть считаны с помощью QR-кода из платёжной квитанции.
  Для этого нажмите на кнопку «*Сканировать QR-код*» в окне «*Реквизиты счёта*» и сканируйте QR-код из платёжной квитанции камерой устройства.
  Реквизиты счёта будут внесены автоматически.
    
  <div class="well">
  Обратите внимание, что описанные выше реквизиты счёта применимы только для банков Российской Федерации.<br>
  Формат реквизитов счёта в других странах может отличаться, и корректная работа с такими данными не гарантируется.<br>  
  QR-код на платёжном документе должен соответствовать стандарту <a href="http://protect.gost.ru/document1.aspx?control=31&id=187312" target="_blank">ГОСТ Р 56042-2014 <sup title="Ссылка откроется в новом окне"><i class="fa fa-external-link-square"></i></sup></a><br>
  Работа с QR-кодами в других форматах невозможна.
  </div>
  
* В секции «*Счёт активен*»:<a id="bill-is-active"></a>  
  
  поставьте флажок, если счёт используется в настоящее время. 
Это означает, что при создании нового месяца счёт автоматически будет добавляться в журнал. 
Если флажок снят, то при создании нового месяца запись о счёте не появится в журнале.
Эта настройка пригодится тогда, когда счёт по каким-то причинам становится недействительным или устаревшим, например, меняется управляющая организация.
При этом вся история платежей по старому счёту останется в журнале. В списке счетов напротив неактивного счёта будет отображаться значок «Замок».

## Сортировка счетов
  
Счета можно отсортировать в списке так, как вам удобно. В [списке платежей по счетам](/help/payments) для выбранного месяца счета будут упорядочены именно таким образом.  

Для сортировки счетов нажмите и удерживайте любой счёт в списке, а затем в появившемся выпадающем меню выберите пункт «Сортировать».
Затем расположите счета так, как нужно, и нажмите галочку «Применить».
  
## Удаление счёта  
  
При удалении счёта удаляется вся информация о нём, включая историю платежей и фото квитанций.
Перед удалением счёта убедитесь, что удаление действительно необходимо, возможно, вы просто хотите, чтобы счёт не добавлялся к новым месяцам в журнале. В этом случае вам нужна настройка «<a href="#bill-is-active" class="page-scroll">Счёт активен</a>».

Если удаление счёта действительно необходимо, удерживайте нужный счёт в списке, а затем в появившемся выпадающем меню выберите пункт «Удалить».
 
</div>