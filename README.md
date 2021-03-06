IDAPython-scripts-for-UEFI-analisys
===================================
.. image:: https://github.com/kyurchenko/IDAPython-scripts-for-UEFI-analisys/blob/master/logo.ico

Все скрипты используются только для анализа дизассемблированных UEFI образов. Автор обращает внимание на то, что скрипты - это ~~результат упорного труда челоека с IQ < 60~~ первичные наброски, которые активно допиливаются.

> __Дисклеймер__
>===============
> Все описанное ниже, как и сами скрипты, должно быть использовано только в образовательных целях.
> Автор не несет ответственности за возможные проблемы, связаннные с непредсказуемостью результатов работы скриптов или Вашей 
> криворукостью!!!

Для использования скриптов необходимо:
======================================
1. Установить на компьютер [Python2.7](https://www.python.org/downloads/release/python-2713/) и выше, настроить переменную окружения 'Path';
2. Установить на компьютер [IDA Pro](https://www.hex-rays.com/products/ida/support/download.shtml) (все работает в версии 6.8), снова поколдовать с переменной окружения;
3. Каким-то чудом достать образ bios.bin;
4. Распаковать образ при помощи [UEFI Extract](https://github.com/LongSoft/UEFITool);
5. Открыть соответствующий файл 'Идой' и применить скрипт;
6. Получать удовольствие!
