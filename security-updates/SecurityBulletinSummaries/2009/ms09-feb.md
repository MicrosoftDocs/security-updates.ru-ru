---
TOCTitle: 'MS09-FEB'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Февраль 2009 г.'
ms:assetid: 'ms09-feb'
ms:contentKeyID: 61236122
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms09-feb(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Февраль 2009 г.
==================================================================

Дата публикации: 10 февраля 2009 г. | Дата обновления: 25 февраля 2009 г.

**Версия:** 2.1

В этом обзоре описаны бюллетени по безопасности, выпущенные в феврале 2009 г.

После выпуска февральских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 5 февраля 2009 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

11 февраля 2009 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в февральской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395122). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

Аннотации
---------

<span></span>
В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе **Продукты, подверженные уязвимости, и соответствующие обновления**.

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название бюллетеня и аннотация</th>
<th style="border:1px solid black;" >Максимальный уровень опасности и воздействие уязвимости</th>
<th style="border:1px solid black;" >Необходимость перезагрузки</th>
<th style="border:1px solid black;" >Подвержены уязвимости</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139814">MS09-002</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности веб-браузера Internet Explorer (961260)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две уязвимости, о которых сообщалось в частном порядке. Все они делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=136636">MS09-003</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Exchange делают возможным удаленное выполнение кода (959239)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две уязвимости Microsoft Exchange Server, о которых сообщалось в частном порядке. Первая делает возможным удаленное выполнение кода при отправке на Microsoft Exchange Server специально созданного сообщения TNEF. Воспользовавшись этой уязвимостью, злоумышленник может получить полный контроль над системой с правами учетной записи службы Exchange Server. Вторая уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot; при отправке на Microsoft Exchange Server специально созданной команды MAPI. Воспользовавшись ею, злоумышленник может заставить службу Microsoft Exchange System Attendant и другие службы, использующие поставщик EMSMDB32, перестать отвечать на запросы.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139513">MS09-004</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в сервере Microsoft SQL Server делает возможным удаленное выполнение кода (959420)</strong><br />
<br />
Данное обновление для системы безопасности устраняет уязвимость сервера Microsoft SQL Server, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода при получении доступа к уязвимой системе непроверенными пользователями или атаке путем внедрения кода SQL. Системы, в которых установлены серверы SQL Server 7.0 с пакетом обновления 4 (SP4), SQL Server 2005 с пакетом обновления 3 (SP3) и SQL Server 2008, не подвержены этой уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128107">MS09-005</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Office Visio делают возможным удаленное выполнение кода (957634)</strong><br />
<br />
Это обновление для системы безопасности устраняет три уязвимости в Microsoft Office Visio, о которых сообщалось в частном порядке. Они делают возможным удаленное выполнение кода при открытии пользователем специально созданного файла Visio. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Приложение Microsoft Office</td>
</tr>
</tbody>
</table>
  
Указатель использования уязвимости  
----------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и кодам CVE.
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности выпуска работающего кода использования уязвимости в течение 30 дней после выпуска бюллетеня по безопасности для каждого обновления для системы безопасности, которое потребуется установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [указателе использования уязвимостей корпорации Майкрософт](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Идентификатор бюллетеня                                   | Название бюллетеня                                                                            | Код CVE                                                                          | Оценка указателя использования уязвимости                                                                          | Ключевые примечания                                                                                                                                                                      |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-002](http://go.microsoft.com/fwlink/?linkid=139814) | Накопительное обновление для системы безопасности веб-браузера Internet Explorer (961260)     | [CVE-2009-0075](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0075) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования   | Может быть создан согласованный код использования.                                                                                                                                       |  
| [MS09-002](http://go.microsoft.com/fwlink/?linkid=139814) | Накопительное обновление для системы безопасности веб-браузера Internet Explorer (961260)     | [CVE-2009-0076](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0076) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования   | Может быть создан согласованный код использования.                                                                                                                                       |  
| [MS09-003](http://go.microsoft.com/fwlink/?linkid=136636) | Уязвимости в Microsoft Exchange делают возможным удаленное выполнение кода (959239)           | [CVE-2009-0098](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0098) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования | (отсутствует)                                                                                                                                                                            |  
| [MS09-003](http://go.microsoft.com/fwlink/?linkid=136636) | Уязвимости в Microsoft Exchange делают возможным удаленное выполнение кода (959239)           | [CVE-2009-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0099) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования | Это уязвимость, связанная с отказом в обслуживании. Атаки с использованием этой уязвимости могут, вероятнее всего, привести к отказу в обслуживании, а не к удаленному выполнению кода.  |  
| [MS09-004](http://go.microsoft.com/fwlink/?linkid=139513) | Уязвимость в сервере Microsoft SQL Server делает возможным удаленное выполнение кода (959420) | [CVE-2008-5416](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-5416) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования   | Опубликован работоспособный код использования после проверки подлинности.                                                                                                                |  
| [MS09-005](http://go.microsoft.com/fwlink/?linkid=128107) | Уязвимости в Microsoft Office Visio делают возможным удаленное выполнение кода (957634)       | [CVE-2009-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0095) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования | (отсутствует)                                                                                                                                                                            |  
| [MS09-005](http://go.microsoft.com/fwlink/?linkid=128107) | Уязвимости в Microsoft Office Visio делают возможным удаленное выполнение кода (957634)       | [CVE-2009-0096](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0096) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования | (отсутствует)                                                                                                                                                                            |  
| [MS09-005](http://go.microsoft.com/fwlink/?linkid=128107) | Уязвимости в Microsoft Office Visio делают возможным удаленное выполнение кода (957634)       | [CVE-2009-0097](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0097) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования | (отсутствует)                                                                                                                                                                            |
  
Продукты, подверженные уязвимости и соответствующие обновления  
--------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
#### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Отсутствует
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8cd902ec-e018-4b61-80f9-825d973f998e)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dd3e2236-9cc0-478e-a46c-981ef685c0e3)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e52aa1fd-e694-4322-b3ff-6abc1b4a16fe)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=218809d6-a9fb-408b-a34d-ab2ac786994c)  
(KB960082)  
(существенный)  
[Windows Internal Database (WYukon) с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e)  
(KB960089)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=edbf1566-b96b-4c7d-98fe-b15f8e766792)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=87183155-6770-4ea2-acca-191de4d40d27)  
(KB960082)  
(существенный)  
[Windows Internal Database (WYukon) x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67)  
(KB960089)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ce78797-d1c0-40d4-84e1-1004389833be)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Отсутствует
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista и Windows Vista с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5f9fa4b6-85a4-43bc-b84f-6bd847799650)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9a8c94b-b9d2-4d64-855f-b5f02ce3dfb5)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2491dbf2-7cd3-44f1-bfad-77e6f760a25c)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e)\*  
(KB960089)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=794373cc-2dce-4ef5-af50-7804c622c230)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67)\*  
(KB960089)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для платформы Itanium
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=11985325-4b33-4077-82cf-6afc7a71c510)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечания для сервера Windows Server 2008**

**\* Подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Это обновление имеет одинаковый уровень опасности для поддерживаемых выпусков Windows Server 2008, независимо от того, выбиралась ли установка основных компонентов сервера при их развертывании или нет. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

**\*\* Не подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Поддерживаемые выпуски Windows Server 2008, при развертывании которых выбиралась установка основных компонентов сервера, не подвержены уязвимости, устраняемой этим обновлением. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

**Примечание к бюллетеню MS09-004**

Сведения о дополнительных файлах обновления см. также в разделе **Серверное программное обеспечение Майкрософт**. Этот бюллетень относится как к операционной системе Windows и ее компонентам, так и к серверному программному обеспечению Майкрософт.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-003**](http://go.microsoft.com/fwlink/?linkid=136636)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange 2000 Server
</td>
<td style="border:1px solid black;">
[Microsoft Exchange 2000 Server с пакетом обновления 3 (SP3) и сборником обновлений, выпущенным в августе 2004 г.](http://www.microsoft.com/downloads/details.aspx?familyid=805dc856-ea60-477d-be40-6ac535a7e7e5)  
(KB959897)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1d9f0956-88bd-4e13-a86b-b1c8d4782f71)\*  
(KB959897)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=93cb3f66-ae72-4356-bdbf-35029cff6df1)\*\*  
(KB959241)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Клиент MAPI для Microsoft Exchange Server и объекты данных совместной работы 1.2.1
</td>
<td style="border:1px solid black;">
[Клиент MAPI для Microsoft Exchange Server и объекты данных совместной работы 1.2.1](http://www.microsoft.com/downloads/details.aspx?familyid=e17e7f31-079a-43a9-bff2-0a110307611e)\*\*\*  
(критический)
</td>
</tr>
</table>
 
**Примечания для MS09-003**

\* Включает средства управления системой Microsoft Exchange в составе сервера Exchange Server 2003, если на сервере запущен активный экземпляр службы Exchange.

\*\* Включает 32- и 64-разрядные выпуски.

\*\*\* Клиент MAPI для Microsoft Exchange Server содержит уязвимый код. Для защиты от уязвимостей, описанных в бюллетене по безопасности MS09-003, пользователи клиента MAPI для Microsoft Exchange Server должны обновить его до версии 6.5.8069. 

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(существенный)  
Обновление QFE:  
[SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2000 с пакетом обновления 4 (SP4) для платформы Itanium
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2000 с пакетом обновления 4 (SP4) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(существенный)  
Обновление QFE:  
[SQL Server 2000 с пакетом обновления 4 (SP4) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Desktop Engine (WMSDE 2000) в системе Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[Microsoft SQL Server 2000 Desktop Engine (WMSDE 2000) в системе Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(существенный)  
Обновление QFE:  
[Microsoft SQL Server 2000 Desktop Engine (WMSDE 2000) в системе Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 Express Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 Express Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS09-004**

Сведения о дополнительных файлах обновления см. также в разделе **Компоненты операционных систем Windows**. Этот бюллетень относится как к операционной системе Windows и ее компонентам, так и к серверному программному обеспечению Майкрософт.

#### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Office Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-005**](http://go.microsoft.com/fwlink/?linkid=128107)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2002
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a30cef3f-9eaf-45bd-9a25-4b65302362cb)  
(KB955654)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Visio 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c9cb589e-1a37-485d-8402-7f42bcd7a1a9)  
(KB955655)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4b711e89-8de2-4f17-8afc-691e0604ff82)  
(KB957831)  
(существенный)
</td>
</tr>
</table>
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-узел [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) (на английском языке) и щелкнув ссылку Latest Security Updates (Последние обновления безопасности).

Обновления для системы безопасности доступны на веб-узлах [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747), [Центра обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130) и [центра загрузки Office](http://go.microsoft.com/fwlink/?linkid=21135). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять нужные обновления в корзину, в том числе на различных языках, и загружать их в указанную папку. Дополнительные сведения см. на веб-узле [Каталог Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=97900) в разделе "Вопросы и ответы".

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставила руководство по диагностике и развертыванию для обновлений безопасности этого месяца. Это руководство также поможет ИТ-специалистам понять, как можно использовать для развертывания обновления для системы безопасности такие средства, как веб-узлы Центра обновления Windows, Центра обновления Майкрософт и центра загрузки Office, анализатор безопасности Microsoft Baseline Security Analyzer (MBSA), средство Office Detection Tool, сервер Microsoft Systems Management Server (SMS) и средство Extended Security Update Inventory Tool (ESUIT). Дополнительные сведения см. в [статье 910723 базы знаний Майкрософт](http://support.microsoft.com/kb/910723).

**Программа Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-узле [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (на английском языке).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-узле [Диспетчер System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx) (на английском языке). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-узле [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939) (на английском языке). Пользователи сервера SMS 2.0 могут также воспользоваться средствами веб-узла [Пакет возможностей служб Software Updates Services](http://go.microsoft.com/fwlink/?linkid=33340) (на английском языке), позволяющими упростить развертывание обновлений для системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-узла безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центры MU, WU и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-узле Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

На веб-узле [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) (на английском языке) содержатся дополнительные сведения о рекомендациях корпорации Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.
-   Обновления для индивидуальных пользователей доступны на веб-узле [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления для системы безопасности, доступные в этом месяце на веб-узле Центра обновления Windows, можно получить в виде файлов образа компакт-диска с выпусками обновлений для системы безопасности в Центре загрузки Майкрософт. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности (на английском языке)**

На веб-узле [Сообщество ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164) (на английском языке) можно получить сведения о способах усовершенствования системы безопасности и оптимизации информационной инфраструктуры предприятия, а также обсудить вопросы, связанные с обеспечением безопасности, с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   компании [TippingPoint](http://www.tippingpoint.com/) и [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-065;
-   Сэма Томаса (Sam Thomas) (<http://eshu.co.uk/>), сотрудничающего с компаниями [TippingPoint](http://www.tippingpoint.com/) и [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, которая описана в бюллетене по безопасности MS09-002;
-   Богдана Матерну (Bogdan Materna) из компании [VoIPshield Systems](http://www.voipshield.com) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-003;
-   Бернхарда Мюллера (Bernhard Mueller) из лаборатории по борьбе с уязвимостями компании [SEC Consult](http://www.sec-consult.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-004;
-   Бина Лю (Bing Liu) из [отдела FortiGuard Global Security Research](http://www.fortiguardcenter.com/) компании Fortinet за сообщение о проблемах, описанных бюллетене по безопасности MS09-005.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (10 февраля 2009 г.). Обзор бюллетеней опубликован.
-   Версия 2.0 (16 февраля 2009 г.). В таблицу подверженного уязвимости программного обеспечения в бюллетене MS09-003 добавлен клиент MAPI для Microsoft Exchange Server.
-   Версия 2.1 (25 февраля 2009 г.). Для MS09-003 добавлено примечание относительно средств управления системой Microsoft Exchange в составе сервера Exchange Server 2003.

*Built at 2014-04-18T01:50:00Z-07:00*
