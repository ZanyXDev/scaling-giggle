# Игра "Гробница Фараона"

Смысл игры состоит в том, чтобы, перемещая иероглифы на входе в очередную комнату гробницы фараона (8Х8), открыть проход. Вы можете менять местами два иероглифа расположенных рядом по вертикали или горизонтали в случае, если при такой перестановке образуется комбинация из трех или более одинаковых картинок в ряд. Такие ряды тут же исчезают, а свободное место заполняется иероглифами "осыпавшимися" сверху. Недостающие иероглифы генерируются случайным образом. За исчезающие иероглифы начисляются очки. За комбинацию из иероглифов даются очки по формуле L+(L+1)^(N-3), но не более 20*L*N, где N - число иероглифов в комбинации, а L - номер уровня. Для того, чтобы перейти с одного уровня на другой, необходимо убрать определённое число иероглифов (на каждом уровне разное). Снизу от панели с иероглифами расположена полоска, отмечающая сколько пройдено и сколько осталось иероглифов.

1-й уровень - 500
2-й уровень - 450
3-й уровень - 400
4-й уровень - 350
5-й уровень - 300
6-й и далее - 50*(L+1)

На первом уровне комбинации составляются из 6 видов иероглифов. С каждым новым уровнем в комбинациях начинает участвовать один новый иероглиф, но всего не более 10 (т.е. начиная с 5-го уровня и далее в игре будет 10 разных иероглифов, не учитывая специальных).

Начиная со 2-го уровня за каждую комбинацию из 4-х и более иероглифов, а также за прохождение каждой четверти уровня игрок получает "свободный" иероглиф - это обычный иероглиф (сгенерированный случайным образом), который хранится у игрока "в кармане" и при необходимости может быть вставлен игроком на любое место, заменив тем самым расположенный там иероглиф.

Начиная с 3-го уровня за каждую комбинацию из 5-ти и более иероглифов, а также за прохождение каждой трети уровня игрок получает "универсальный ключ", подходящий к любой комбинации иероглифов и к нескольким разным комбинациям одновременно.

Начиная с 4-го уровня за каждую комбинацию из 6-ти и более иероглифов, а также за прохождение половины уровня игрок получает "искривитель пространства", позволяющий, при его применении, сделать 3 хода (не обязательно подряд) по диагонали.

У игрока не может быть одновременно более 1 дополнительного иероглифа каждого типа (1 простой, 1 джокер и 1 искривитель).

Игра заканчивается, если игрок не может составить ни одной комбинации имеющимися у него в распоряжении иероглифами. 
