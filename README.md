# "Помнить все" на 1С Элемент + Телеграм

Вы можете напомнить себе о задаче, введя (или надиктовав) подобные фразы:  
позвонить через 15 минут    
напомнить завтра утром   
погулять в 8 вечера в воскресенье  
и даже   
вынести мусор в последний понедельник следующего месяца без четверти пять  

Давным-давно была программа «Помнить все» под андроид, позволяющая задавать напоминания голосом. 
Правда, на последних версиях она уже не работает. 

Здесь сделана попытка выполнить подобный разбор на старых добрых регулярных выражениях. К переданному тексту последовательно применяются регулярные выражения, пытаясь найти в тексте описание даты/времени. Если часть строки точно не нужно анализировать, можно обрамить ее двойными угловыми скобками <<это не дата>>.   

Напоминание придет в привязанный телеграм-бот.

Полное описание приведено в статье (https://infostart.ru/1c/articles/2293765/)

[Infostart](https://infostart.ru/bitrix/templates/sandbox_empty/assets/tpl/abo/img/logo.svg)





