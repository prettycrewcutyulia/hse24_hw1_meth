# hse24_hw1_meth
 Изучение глобального изменения уровня CpG метилирования ДНК при раннем эмбриональном развитии мыши. 
 
 Колаб: https://colab.research.google.com/drive/1iTj0eqRpdTTekPzy4BM5voKEYlvzPoG-#scrollTo=bAaOdZCKsVtX
## Анализ QC прочтений
![](/screenshots/fastqc.png)
Отчет: https://github.com/prettycrewcutyulia/hse24_hw1_meth/blob/main/data/report_fastqc.html
Отличие от секвенирования ДНК или РНК заключается в необычном GC-составе, который обусловлен применением бисульфитной конверсии. Этот процесс преобразует неметилированный цитозин в урацил при использовании бисульфитного секвенирования.
## Работа с bam-files с выравниваниями BS-seq ридов на 11-ю хромосому мыши
![](/screenshots/выравнивание.png)
## Дедупликация
![](/screenshots/дупликация.png)
## Описание M-bias plot
В отчетах представлены графики, отражающие уровень метилирования на хромосому. Наибольшая доля метилирования наблюдается в образце Epiblast (77-78%), затем в образце 8_cell (42-45%), а наименьшая доля метилирования у образца icm (22-24%).

### 8cell – 8-клеточный эмбрион, примерно 2.25 дня после оплодотворения яйцеклетки.
![](/screenshots/8_part1.png)
![](/screenshots/8_part2.png)
Отчет: https://github.com/prettycrewcutyulia/hse24_hw1_meth/blob/main/data/8cell.html
### ICM – внутренняя клеточная масса бластоциста, примерно 3.5 дня после оплодотворения яйцеклетки.
![](/screenshots/icm_part1.png)
![](/screenshots/icm_part2.png)
Отчет: https://github.com/prettycrewcutyulia/hse24_hw1_meth/blob/main/data/icm.html
### Epiblast – стадия эпибласта, примерно 6.5 дней после оплодотворения яйцеклетки.
![](/screenshots/epi_part1.png)
![](/screenshots/epi_part_2.png)
Отчет: https://github.com/prettycrewcutyulia/hse24_hw1_meth/blob/main/data/epiblast.html

## Гистограмма распределения метилирования цитозинов по хромосоме
У образца Epiblast наблюдается высокий уровень метилирования ДНК, в то время как для 8_cell этот показатель невелик, а для ICM практически отсутствует. Это может указывать на изменение уровня метилирования на различных стадиях развития эмбриона. Пример скрипта для построения графиков можно найти в ноутбуке.
![](/screenshots/8cell.png)
![](/screenshots/epiblast.png)
![](/screenshots/icm.png)
## Уровень метилирования и покрытия
### Покрытие
![](/screenshots/image_cov.png)
### Метилирование
![](/screenshots/image_meth2.png)
