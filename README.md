# week_02_lecture_01_exercises


###Exercises

Complete each exercise to the best of your ability. Follow the instructions and save your files to your week_2_lecture_1_exercises Github repository. Any short answer questions may require some additional research on your part.

1.Using precedence, override the thirdBox with both box and special class to have a difference background color. Save the index.html and style.css files to a folder called precedence.


    <!--  index.html -->
    <html>
      <head>
        <meta charset="utf-8">
        <title>Colored Boxes</title>
        <link rel="stylesheet" href="styles.css">
      </head>
      <body>
        <div id="firstBox" class="box"></div>
        <div id="secondBox" class="box"></div>
        <div id="thirdBox" class="box special"></div>
      </body>
    </html>

    /* style.css */

    body{
        text-align: center;
    }

    .box{
        background-color: yellow;
        width: 100px;
        display: inline-block
        height: 100px;
    }
