# coursework-NP-completeness-minimum-spanning-tree
Analysis of the minimum spanning tree problem (Анализ задачи о минимальном остовном дереве)

### Аннотация

В работе рассматривается задача поиска такого остовного дерева в графе 𝐺 = (𝑉, 𝐸), что максимальная степень вершин дерева (далее степень дерева) минимальна. Приведено доказательство факта, что проверка существования остовного дерева степени не выше 𝑘 является 𝑁 𝑃 -полной для любого фиксированного 𝑘 ě 2. Представлен алгоритм поиска аппроксимированного остовного дерева, степени не более чем на единицу превышающего степень оптимального дерева, работающий за полиномиальное время.

Работа состоит из двух частей: теоретической и практической. Теоретическая часть работы включает в себя частичное изложением статьи F ̈urer и Raghavachari [7] 1994 года. Переведены две леммы, две теоремы, идеи алгоритма, сам алгоритм, доказательство оценки времени работы. Мной добавлен ряд уточнений в доказательства утверждений, тем самым они стали более подробными и понятными. Пошаговый алгоритм был изменён по сравнению с оригиналом для удобства реализации на языке Python.
