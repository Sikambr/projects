---
layout: page
title: ExportToDBF
permalink: /exporttodbf/
---

<b>2014</b>, Java, JDBC.

Приложение разработано для автоматизации экспорта из баз данных, описанных в 
[XML-файле](https://drive.google.com/file/d/0B1nIE1BTDG6zNHdVVGlmb2JuOE0/view?usp=share_link&resourcekey=0-yE4tbHyDcSPryVT0_SK43A)
, в dBase формат.

В 
[XML-файле](https://drive.google.com/file/d/0B1nIE1BTDG6zNHdVVGlmb2JuOE0/view?usp=share_link&resourcekey=0-yE4tbHyDcSPryVT0_SK43A)
описываются как источники с запросами, так и структура файлов-приемников.

Источником может быть любая база данных, для которой имеется JDBC драйвер.

В приложении ведется лог экспорта.

В архиве с исходными кодами находится документация в формате Javadoc.

### Используемые дополнительные библиотеки:

* [interclient.jar](https://github.com/ForNeVeR/interclient) – Interbase JDBC драйвер
* [ini4j.jar](http://ini4j.sourceforge.net/download.html) – библиотека для обработки Windows ini-файлов.

### Файлы для скачивания:

* [ExportToDBF.jar](https://drive.google.com/file/d/0B1nIE1BTDG6zZHlRbWFRaHRhQmM/view?usp=sharing&resourcekey=0-xTimr4XiwfoNU0vJUXmlQg)
* [ExportToDBF-sources.zip](https://drive.google.com/file/d/0B1nIE1BTDG6zeWZRc2I3TnIxNTg/view?usp=sharing&resourcekey=0-zVAEKtWWdZ9zHJaeB_GONQ) - исходные коды.
* [Rents.J.xml](https://drive.google.com/file/d/0B1nIE1BTDG6zNHdVVGlmb2JuOE0/view?usp=share_link&resourcekey=0-yE4tbHyDcSPryVT0_SK43A) - пример файла-описателя источников и приемника.

![{{ page.title }}]({{ site.baseurl }}/images/exporttodbf.jpg)
