<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Семья Лапиных | Генеалогическое древо</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
background:#efe4c8;
font-family:Georgia,serif;
color:#4b2d14;
padding:40px;
}

h1{
text-align:center;
font-size:42px;
margin-bottom:10px;
}

h2{
text-align:center;
font-size:22px;
margin-bottom:50px;
color:#8b5a2b;
}

.tree{
display:flex;
justify-content:center;
}

.tree ul{
padding-top:25px;
position:relative;
display:flex;
justify-content:center;
}

.tree li{

list-style:none;
text-align:center;
position:relative;

padding:20px 8px 0 8px;

}

.tree li::before,
.tree li::after{

content:'';
position:absolute;
top:0;
right:50%;

border-top:2px solid #8b6d45;

width:50%;
height:25px;

}

.tree li::after{

right:auto;
left:50%;

border-left:2px solid #8b6d45;

}

.tree li:only-child::before,
.tree li:only-child::after{

display:none;

}

.tree li:only-child{

padding-top:0;

}

.tree li:first-child::before{

border:none;

}

.tree li:last-child::after{

border:none;

}

.tree li:last-child::before{

border-right:2px solid #8b6d45;
border-radius:0 8px 0 0;

}

.tree li:first-child::after{

border-radius:8px 0 0 0;

}

.tree ul ul::before{

content:'';

position:absolute;

top:0;
left:50%;

border-left:2px solid #8b6d45;

width:0;

height:25px;

}

.person{

display:inline-block;

background:#f9efd8;

padding:10px 18px;

border:2px solid #8b6d45;

border-radius:10px;

cursor:pointer;

transition:.3s;

font-weight:bold;

min-width:180px;

}

.person:hover{

background:#fff7e8;

transform:scale(1.05);

box-shadow:0 0 15px rgba(0,0,0,.25);

}

#info{

position:fixed;

right:20px;

top:20px;

width:320px;

background:white;

border:3px solid #8b6d45;

border-radius:12px;

padding:20px;

display:none;

box-shadow:0 0 25px rgba(0,0,0,.35);

}

#info h3{

margin-bottom:10px;

}

#close{

float:right;

cursor:pointer;

font-size:22px;

}

@media(max-width:1000px){

body{

overflow:auto;

}

.tree{

width:max-content;

}

}

</style>

</head>

<body>

<h1>Семья Лапиных</h1>

<h2>Генеалогическое древо XIX–XXI век</h2>

<div id="info">

<div id="close">✖</div>

<h3 id="title"></h3>

<p id="text"></p>

</div>

<div class="tree">

<ul>

<li>

<div class="person" onclick="showInfo('Василий Емельянович Лапин','Основатель известной ветви семьи Лапиных. Родился в Кашине (по семейным сведениям).')">

Василий Емельянович Лапин

</div>

<ul><li>

<div class="person" onclick="showInfo('Надежда','Дочь Василия Емельяновича.')">
Надежда
</div>

<ul>

<li><div class="person" onclick="showInfo('Евгения','III поколение семьи Лапиных.')">Евгения</div></li>

<li><div class="person" onclick="showInfo('Анастасия','III поколение семьи Лапиных.')">Анастасия</div></li>

<li><div class="person" onclick="showInfo('Вера','III поколение семьи Лапиных.')">Вера</div></li>

</ul>

</li>



<li>

<div class="person" onclick="showInfo('Борис','Сын Василия Емельяновича.')">
Борис
</div>

</li>



<li>

<div class="person" onclick="showInfo('Георгий','Сын Василия Емельяновича.')">
Георгий
</div>

<ul>

<li>

<div class="person" onclick="showInfo('Тамара','Дочь Георгия.')">
Тамара
</div>

<ul>

<li>

<div class="person" onclick="showInfo('Юрий','IV поколение.')">
Юрий
</div>

</li>

</ul>

</li>

</ul>

</li>



<li>

<div class="person" onclick="showInfo('Владимир','Сын Василия Емельяновича.')">
Владимир
</div>

<ul>

<li>

<div class="person" onclick="showInfo('Георгий Владимирович','III поколение.')">
Георгий
</div>

</li>

</ul>

</li>



<li>

<div class="person" onclick="showInfo('Леонид','Сын Василия Емельяновича.')">
Леонид
</div>

</li>



<li>

<div class="person" onclick="showInfo('Сергей','Сын Василия Емельяновича.')">
Сергей
</div>

<ul>

<li>

<div class="person" onclick="showInfo('Нина','III поколение.')">
Нина
</div>

</li>

<li>

<div class="person" onclick="showInfo('Алла','III поколение.')">
Алла
</div>

</li>

<li>

<div class="person" onclick="showInfo('Михаил Сергеевич Лапин','Участник Великой Отечественной войны. Воевал под Сталинградом в 1942–1943 годах.')">
Михаил
</div>

<ul>

<li>

<div class="person" onclick="showInfo('Игорь','IV поколение семьи.')">
Игорь
</div>

<ul>

<li>

<div class="person" onclick="showInfo('Дмитрий Игоревич Лапин','Сын Игоря. Живёт в Санкт-Петербурге.')">
Дмитрий
</div>

<ul>

<li>

<div class="person" onclick="showInfo('Игорь Дмитриевич Лапин','Твой брат.')">
Игорь Дмитриевич
</div>

</li>

<li>

<div class="person" onclick="showInfo('Максим Дмитриевич Лапин','Родился в 2015 году. Сын Дмитрия Игоревича и Татьяны Николаевны Лапиной.')">
Максим Дмитриевич
</div>

</li>

</ul>

</li>

</ul>

</li>

</ul>

</li>

</ul>

</li>

</ul>

</li></ul>

</div>

<script>

function showInfo(name,text){

document.getElementById("info").style.display="block";
document.getElementById("title").innerHTML=name;
document.getElementById("text").innerHTML=text;

}

document.getElementById("close").onclick=function(){

document.getElementById("info").style.display="none";

}

</script>

<hr style="margin-top:60px;">

<div style="text-align:center;color:#6b4a2d;font-size:18px;line-height:1.8;">

<b>Семья Лапиных</b><br>

Электронное генеалогическое древо семьи Лапиных.<br>

Создано Максимом Дмитриевичем Лапиным.<br>

2026 год.

</div>

</body>

</html>
