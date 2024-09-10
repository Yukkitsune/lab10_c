Дан класс (например, с именем Vector), задающий вектор размерности n. Поля
класса: указатель на массив, задающий вектор (тип элемента int или double в зависимости
от варианта), массив должен создаваться динамически, число элементов (размерность)
вектора (тип int). Класс включает: конструктор без параметров, задающий пустой вектор
(число элементов равно 0), конструктор, создающий объект вектор на основе обычного
одномерного массива размерности n, конструктор копирования, конструктор
перемещения, деструктор.
Необходимо перегрузить операции и продемонстрировать их работу. Перегрузить
операцию [] (обращение к элементу вектора по индексу), операцию = (присваивание с
копированием), операцию = (присваивание с перемещением), а также операцию вставки
(<<) объекта в поток cout или в файл (объект класса ostream) и операцию извлечения (>>)
объекта из потока cin или из файла (объект класса istream). Также продемонстрировать
разницу между конструктором копирования и конструктором перемещения и между
операциями присваивания с копированием и перемещением. Исходные коды класса
разместить в двух файлах: в заголовочном файле класса и файле реализации класса.
При выполнении работы все входные данные читаются из текстового файла
input.txt (создать этот файл любым текстовым редактором), результаты выводятся в
файл output.txt. В отчете представить содержимое этих файлов

Описание операции перегруженной операции - ^ побитовая операция исключающая ИЛИ с двумя векторами одинаковой размерности, на выходе вектор такой же размерности элемент, которого равен битовой операции ^ соответствующих элементов двух векторов
Тип элемента вектора (массива) - int
Типы операндов и результата для перегруженной операции - Vector, int * 
Результат - Vector
