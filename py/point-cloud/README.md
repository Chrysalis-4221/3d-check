# Алгоритм

На вход подается облако точек, которое затем обрабатывается:

1. калибруется
1. удаляются выбросы
1. сегментируется

После этого к облаку точек применяется метод Левенберга-Марквардта, расширенный фильтр Калмана и триангуляция Делоне методом заметающей прямой. Затем программа выводит финульную 3d модель.

## Алгоритм выполнения

1. Загрузка облака точек
1. Калибровка, сегментация
1. Применение алгоритма Левенберга-Марквардта
1. Применение расширенного фильтра Калмана
1. Применение триангуляции Делоне методом заметающей прямой
1. Построение 3d модели
