# test-gap
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        html,
        body {
            height: 100%;
            /* высота элементов в процентах */
            margin: 0;
            /* убираем внешние отступы со всех сторон */
            overflow: auto;
            /* полоса прокрутки будет добавлена автоматически при переполнении элемента */
        }

        .grid-container,
        .grid-container2 {
            display: grid;
            /* элемент отображается как блочный   grid-контейнер */
            margin-top: 5px;
            /* внешний отступ сверху */
            padding: 12px;
            /* внешний отступ элемента со всех сторон */
            background: rgb(0, 150, 208);
            /* цвет заднего фона */
        }

        .grid-container>div,
        .grid-container2>div {
            background: rgb(241, 101, 41);
            /* цвет заднего фона */
            border: 1px solid #000;
            /* сплошная граница размером 1 пиксель черного цвета */
            text-align: center;
            /* горизонтальное выравнивание текста */
        }

        .grid-container {
            grid-template-columns: 50px auto 100px;
            grid-gap: 10px;
            /* задаем промежуток между строками и столбцами в макете сетки */
        }

        .grid-container2 {
            height: 50%;
            /* высота элемента в процентах */
            grid-template-columns: auto auto auto;
            grid-gap: 10% 20px;
            /* задаем промежуток между строками и столбцами в макете сетки */
        }
    </style>
</head>

<body>
    <div class="grid-container">
        <div>A</div>
        <div>B</div>
        <div>C</div>
        <div>D</div>
        <div>E</div>
        <div>F</div>
    </div>
    <div class="grid-container2">
        <div>A</div>
        <div>B</div>
        <div>C</div>
        <div>D</div>
        <div>E</div>
        <div>F</div>
    </div>
</body>
</html>
