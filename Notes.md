## Useful commands

* print in the console: DBMS_OUTPUT.PUT_LINE('Your text here'); --- not case-sensitive, т.е. dbms_output.put_line тоже норм
* / в конце процедуры - execute the script automatically

## Мысли при чтении учебника

* Триггеры и курсоры объявляются в декларативном блоке процедуры. Так что триггер - зверь вспомогательный
 и не конкурент процедуре. Совсем.
* В документации Оракла говорится, что функция отличается от процедуры только тем, что обязана 
что-то вернуть вызывающему, а процедура - нет. Так что для простоты в документации и то, и другое
обозначается общим термином "процедуры"

## ХЗ почему так

* DECLARE при регистрации функции в пакете ломает код, просто объявить переменные между IS и BEGIN