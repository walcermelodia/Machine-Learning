# Определение числа на изображении

В качестве данных используются изображения из базы данных 
MNIST.

Изображение размером 28×28 представляется в виде последовательности из 784 чисел — по одному 
числу на каждый пиксель изображения. Каждое число находится в диапазоне от 0 до 255.

Нулевой интенсивности соответствует абсолютно чёрный пиксель, максимальной — абсолютно белый.

Для распознавания чисел на изображении используются модели дерево принятий решений и случайный лес.