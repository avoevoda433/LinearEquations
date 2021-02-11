# LinearEquations
Программа, которая решает системы линейных уравнений с равным количеством переменных и уравнений.

### Установка:  
Для установки используем терминал и ОС Linux Ubuntu.

1. Клонирование github репозитория  
`git clone https://github.com/avoevoda433/LinearEquations.git` 

2. Выбираем папку проекта  
`cd LinearEquations`  

3. Собираем проект  
`make`  
Устанавливаем программу  
`sudo make install`  

4. После установки программа запускается командой  
`linEq`

5. Для удаления программы используем  
`make clean`  
`sudo make uninstall`   

### Начало работы:  
Перед запуском программы необходимо создать текстовый файл `name.txt` (вместо `name` указываете свое имя файла).  

Открываем терминал, выбираем директорию, в которой будет создан файл (вместо `dir1/dir2` указываете свой путь к директории)  
`cd dir1/dir2`  

Создаем файл  
`touch name.txt`  

Узнаем путь к файлу и копируем его  
`realpath name.txt`  

![](https://sun9-16.userapi.com/impf/o-fa5Xcu73SOiMr9yH_QQ9jMglq0J0oRAV-g4Q/yPA4yzKK1Js.jpg?size=554x143&quality=96&proxy=1&sign=293628f520ac981c34f9a98ff2994834&type=album)  

Открываем файл и записываем в него расширенную матрицу системы линейных уравнений с одинаковым количеством переменных и уравнений. Элементы матрицы разделяем пробелами, либо табуляцией.  
![](https://sun9-5.userapi.com/impf/nm5klqwWUNQJvZJRlJWAFeqhbQsQc076UzqDDQ/lclOutrItco.jpg?size=254x131&quality=96&proxy=1&sign=63de9a82f87165dcd90ce24bb18d5217&type=album)  

Запускаем в терминале программу командой `linEq` и вставляем путь к файлу  
![](https://sun9-73.userapi.com/impf/OVo48V5vh0WXSnHAndW1jis92HRpvQ3yVWRrAQ/sMCfU4t-89c.jpg?size=556x177&quality=96&proxy=1&sign=df455df34314674da967b86e5e2772e5&type=album)  

После выполнения программы результат будет записан в файл, в противном случае будет выведено сообщение об ошибке  
![](https://sun9-54.userapi.com/impf/DhuADSt4b_KJ91Dc7N7bBhHiDtP7ZxH3o3yfrw/fSNHbhvPYdY.jpg?size=804x233&quality=96&proxy=1&sign=503168ea8b43c1a2a312160d1368ed07&type=album)  
![](https://sun9-12.userapi.com/impf/83KKZYG6hyDJVzHcyRNl8SwmbMlHRrp7WO1P0A/73TxmPilM60.jpg?size=246x179&quality=96&proxy=1&sign=c61fc5c98bb63b8077ce6eb29be96bd1&type=album)
