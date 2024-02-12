<p align="center">
  <a href="https://github.com/avsavin/PROJECT-6" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Кластеризация изображений транспортных средств</h3>

---

<p align="left"> 
    <br> Один из ключевых проектов IntelliVision — Smart City/Transportation, система, обеспечивающая безопасность дорожного движения и более эффективную работу парковок. С помощью Smart City/Transportation можно контролировать сигналы светофоров и соблюдение ограничений скорости, определять виды транспортных средств, распознавать номерные знаки, считать автомобили и людей.

    Для модификации и повышения эффективности системы Smart City/Transportation команде необходимо автоматизировать определение дополнительных параметров авто на изображении:

        * тип автомобиля (кузова),
        * ракурс снимка (вид сзади/спереди),
        * цвет автомобиля,
        * другие характеристики.

Также необходимо автоматизировать поиск выбросов в данных (засветы и блики на изображениях, изображения, на которых отсутствуют автомобили и т. д.).
</p>

## Table of Contents

- [Getting Started](#getting_started)
- [Usage](#usage)


## Getting Started <a name = "getting_started"></a>

### Prerequisites

Требования к установленному программному обеспечению находятся в файле requirements.tct

### Installing

1) Исходные данные и разархивируйте их в под-директорию Вашего ноутбука. Загрузить их можно по ссылке https://drive.google.com/file/d/1vkQaj0Lr4Jwkumli7k9IzCtxFP1tIoXH/view

2) Загрузите и разархивируйте результаты промежуточных вычислений:  https://drive.google.com/file/d/1WrUQGAGnwOS18oys8Z8Ccv-2QqaBTf0u/view?usp=sharing


3) Укажте путь к файлам в переменных input_path и output_path в ячейке 7 ноутбука
Например:
    input_path = './IntelliVision_case/'
    output_path = './output/'

## Usage <a name="usage"></a>

После запуска ноутбук попытается загрузить промежуточные данные из каталога "output_path". Если данные отсутствуют, ноутбук попытается сделать расчет и сохранить результаты для последующего использования. 

