# Sorting by pattern

Сортируем столбцы в матрице (csv,xls,xlsx) по шаблону

## Getting Started

Имеем эталонную матрицу main, и secondary матрицу в которой нужно отсортировать столбцы по шаблону(main)
Матрицы берутся из той же папки где находится скрипт

Добавил интерактивный режим, теперь прописывать в файле ничего не нужно. (Возможность руками прописать файлы пока оставил... ну мало ли...) 
При запуске скрипта он сканирует папку на наличие csv, xls, xlsx файлов. Потом спрашивает юзера какой ему файл брать как эталонный(main), и какой файл нужно обработать(secondary). 
После работы скрипта создается новый файл который помечается как upd_secondary_name

Для работы скрипта требуется *Pandas 0.19.2* - данная версия стоит на наших энвах. 
В новых версиях Pandas было много изменений, за корректную работу скрипта не ручаюсь.
