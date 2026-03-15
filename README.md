# Atividade-PI-Flexbox-02-

## HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flex-box</title>
    <link rel="stylesheet" href="estilo.css">
</head>

<body>

    <div class="base container1">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>
    <div class="base container2">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>
    <div class="base container3">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>
    <div class="base container4">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>
    <div class="base container5">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>
    <div class="base container6">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>

     <div class="base container-exercicioB">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>

     <div class="base container-desafio">
        <div class="flex-item box1"><h1>1</h1></div>
        <div class="flex-item box2"><h1>2</h1></div>
        <div class="flex-item box3"><h1>3</h1></div>
        <div class="flex-item box4"><h1>4</h1></div>
    </div>

</body>

</html>


## CSS


.flex-item {
    width: 100px;
    height: 100px;
    border-radius: 4px;
    display: flex;
    align-items: center;
}

.base {
    margin-bottom: 15px;
    background-color: #d0d3d4;
    border-radius: 4px;
}

.box1 {
    background-color: #63b1bc;
}

.box2 {
    background-color: #1f2a44;
}

.box3 {
    background-color: #ed145b;
}

.box4 {
    background-color: #efb661;
}

h1 {
    width: fit-content;
    margin: auto;
}

/* Insira o código abaixo */

.container1 
{
   display: flex; 
}

.container2 
{
   display: flex; 
   align-items: flex-end;
   justify-content: flex-end;
   flex-direction: row;
}

.container3
{
   display: flex;
   align-items: flex-start;
   justify-content: center;
   flex-direction: row;
}

.container4 
{
    display: flex;
    justify-content: space-between;
    flex-direction: row;
}
.container5 
{
    display: flex;
    align-items: flex-end;
    justify-content: space-around;
    flex-direction: row;

}
.container6 
{
    display: flex;
    justify-content: space-evenly;
    flex-direction: row;
}

.container-exercicioB
{
    display: flex;
    align-items: flex-end;
    justify-content: flex-end;
    flex-direction: row-reverse;
}

.container-desafio
{
     display: flex;
    flex-direction: column-reverse;
}
