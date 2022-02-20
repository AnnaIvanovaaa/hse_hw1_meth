# hse_hw1_meth
ссылка на гугл колаб https://colab.research.google.com/drive/1yJmrqgGIAeKabzC6JjRWFbljGwLvTDGf#scrollTo=c5QMGKJYxrza


# Число ридов, закартированных на участках 11347700-11367700; 40185800-40195800
| Образцы       | 11347700-11367700  | 40185800-40195800 |
| ------------- |:------------------:| -----------------:|
| 8cell         | 1090               | 464               |
| epiblast      |2328 | 1062   |
| ICM           |   1456       |  630   |

# Дедупликация образцов
Процент и кол-во прочтений дуплицированных в каждом из образцов
| Образцы       | % прочтений  | 
| ------------- |:------------------:| 
| 8cell         | 18.31%               |
| epiblast      | 2.92% |
| ICM           |   9.08%       |

*8cell:*
![newplot](https://user-images.githubusercontent.com/93247992/154564300-dfc0839d-701d-4f9a-8124-1687f53ecd2c.png)
*epiblast:*
![newplot (6)](https://user-images.githubusercontent.com/93247992/154866680-da5057e0-4d97-456e-9c6a-6daa706057b0.png)
*ICM:*
![newplot (5)](https://user-images.githubusercontent.com/93247992/154866693-9194cc17-bb00-46ee-933b-20a83a45238f.png)

# Какие особенности можно наблюдать по сравнению с секвенированием ДНК или РНК? 
Основываясь на теории, которая описывалась в мануале "Bismark  Bisulfite Mapper", стоит уточнит несколько аспектов, которые важны в описании особенностей секвенирования. Изначально происходит преобразование прямого и обратного чтения (+ и - стренд), т.е. изменение цитозина (C) на тимин (T), и, соответственно, гуанин (G) на аденин (A). Так, анализ состояниий метилирования некоторых позиций цитозина в риде происходит засчет преобразования геномов и их дальнейшее выравнивание с бесульфитными геномами. 
# Описание M-bias plot
*8cell:*

![Bismark M-bias Read 1](https://user-images.githubusercontent.com/93247992/154564440-232fadf0-f910-4cd7-aae7-847d078e45fa.png)
![Bismark M-bias Read 2](https://user-images.githubusercontent.com/93247992/154564434-85d3e42b-4a49-4c3c-a2ba-79517c7f1ba3.png)

*epiblast:*
![Bismark M-bias Read 1 (1)](https://user-images.githubusercontent.com/93247992/154866739-8a845460-5604-4f24-9c9c-3809257b4631.png)
![Bismark M-bias Read 2 (1)](https://user-images.githubusercontent.com/93247992/154866752-b2f858e0-7967-419d-a502-235f30479df9.png)


