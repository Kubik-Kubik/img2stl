# img2stl

get_model_from_img(img: str, scale_reduction = 1, maxHeight = 100, invert = False)

Создает 3D модель в формате .stl на основе изображения в форматах(.jpg, .png)

Принцип работы:
Изображение приводится к черно-белому виду. Каждый пиксель изображения создает вершину в 3D-модели, положение XY задается положением пикселя на изображении, а высота Z - оттенком серого.

Примеры работы алгоритма:
![alt text](http://url/to/img.png)

#1
![image](https://github.com/Kubik-Kubik/img2stl/blob/main/8.png)
