# Описание работы схемы(краткое)

Мы предлагаем разработать некую "систему управления", в которой вы сможете управлять всем процессом, которая будет иметь максимальную гибкость в плане расширения функционала.

В неё будет интегрирован парсер, который будет настраиваться через удобный интерфейс этой системы.
Система пробегается по ресурсам для парсинга, получая данные с них(через API пославщика, xml файл, либо вытаскивая из html страницы нужную информацию).
Полученные данные сохраняются в системе управления, и интернет магазины по API этой системы получают обновленные данные.

В систему также можно интегрировать управление интернет магазинами(в этом случае битрикс исключен, его монолитность очень сильно замедлит процесс)

Если этот принцип работы вам подходит, то мы начинаем формировать этапы разработки. Если нет - то сначала мы утвердим схему работы.
