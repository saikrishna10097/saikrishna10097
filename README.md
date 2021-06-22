<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link href="../Css/index.css" rel="stylesheet">
</head>
<body>
    <div class="header">
        <img src="../images/gnitLogo.png">
        <h1>Guru Nanak Institute Of Technology</h1>        

    </div>




body{
    background-color:bisque;
}
.header{
    display:flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
.header > img{

    object-fit: contain;
    height:60px;
}

.header> h1{
    padding-top: 10px;
    font-family: Helvetica, sans-serif;
    font-style: bold;
    font-weight: 800;
