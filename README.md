# test-gap

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


