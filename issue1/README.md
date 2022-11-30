Шаги для запуска:
0) Extra: проверить подключение к общей папке
> $ cd /Users/saniya/AAA_HW_instruments_new

1) В файле main.py запускаем "Run Doctest encode"
Проверяется работа тестов, использование директивы и флагов.
> $ python -m doctest -o NORMALIZE_WHITESPACE -v issue1/test_morse_encode.py

4) Передаем в result 
> $ python -m doctest -o NORMALIZE_WHITESPACE -v issue1/test_morse_encode.py > issue1/result
