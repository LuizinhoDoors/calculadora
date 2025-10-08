<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Code Start</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
     <div class="calculator">
         <div class="display" id="display"></div>
         <div class="buttons">
            <button class="button light-red">clear</button>
            <button class="button dark-gray">/</button>
            <button class="button dark-gray">*</button>
            <button class="button dark-gray">7</button>
            <button class="button dark-gray">8</button>
            <button class="button dark-gray">9</button>
            <button class="button dark-gray">-</button>
            <button class="button dark-gray">4</button>
            <button class="button dark-gray">5</button>
            <button class="button dark-gray">6</button>
            <button class="button dark-gray">+</button>
            <button class="button dark-gray">1</button>
            <button class="button dark-gray">2</button>
            <button class="button dark-gray">3</button>
            <button class="button dark-gray wide">0</button>
            <button class="button dark-gray">00</button>
            <button class="button dark-gray">.</button>
            <button class="button light-blue">=</button>
         </div>
     </div> 

     <script src="script.js"></script>
</body>
</html>


css-----------------------------------------------------------------------------------------------------------


body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: black;
    margin: 0;
}

.calculator{
    background-color: rgb(66, 65, 65);
    padding: 20px;
    border-radius: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    text-align: center;
    width: 320px;
}

.display{
    background-color: #222;
    color: #fff;
    font-size: 20px;
    padding: 10px;
    border-radius: 10px;
    margin-bottom: 20px;
    min-height: 50px;
    text-align: right;
}

.buttons{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
}

.button{
    border: none;
    border-radius: 50%;
    padding: 20px;
    font-size: 2.screm;
    cursor: pointer;
}

.button.dark-gray{
    background-color: #333;
    color: #fff;
}

button.light-red{
    background-color: red;
    color: #fff;
}

.button.light_blue{
    background-color: lightblue;
    color: blue;
}

.button-wide{
    grid-column: span 2;
    border-radius: 50px;
}
