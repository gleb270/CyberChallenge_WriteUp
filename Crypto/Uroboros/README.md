# Uroboros

## Задание

Наш скрипт, похоже, немного повредился. Но мы вспомнили, что в результате он выводил строку
2E\x18fQ)61X@\x10j\x0bjJ+ <\x1fH\x0cuD/Ll

## Решение

Можно увидеть то, что в прикрепленном файле **uroboros.py** используется шифрование xor, а т.к. есть свойство **x xor y = z** , то **z xor y = x** значит можно задать в обратную сторону полученную строку

Получаем флаг: **CC{w45_17_cryp70_0r_wh47?}**
