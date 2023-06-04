# Сегментация фотографий рака кожи

В данном проекте решается задача сегментации раковых новообразований на коже с целью автоматизации и повышения точности процессов отделения здоровой кожи от опухоли. 

Ссылка на dataset: https://www.fc.up.pt/addi/ph2%20database.html


## Рассматриваемые архитектуры:

- U-Net, функция потерь бинарная кросс-энтропия
<image src="U-Net.png">
- SegNet, функции потерь бинарная кросс-энтропия, dice cofficient, focal, Tversky loss
<image src="SegNet.png">

## Технологический стек:
- PyTorch
- Seaborn
- Scikit-image
- Numpy

Во время обучения SegNet с функцией потерь Tversky loss показала себя лучше других моделей 
## Пример изображений и готовых масок

<image src="example.png">