Reto completado en el siguiente codigo
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Reto Css 11</title>
        <style>
            body 
            {
                font-family: Arial, Helvetica, sans-serif;
                background-color:lightslategrey;
            }
            .container
            {   
                display: grid;
                grid-template-columns: 200px 200px 85px;
                grid-template-rows: 100px 100px 100px 100px 100px 100px;
                grid-gap:30px;
                background: white;
                border-radius: 5em;
                padding: 5em;
                margin: 15em;
                height: 700px;
                width: 560px;
            }
            .item-1
            {
                padding: 2em;
                border-radius: 3em;
                grid-column-start: 1;
                grid-column-end: 3;
                background-color: rgba(152, 173, 192, 0.966);
                color: rgba(63, 72, 82,0.9);
                font-size: 21px;
            }
            .item-2
            {
                padding: 25px;
                border: 1px solid rgba(152, 173, 192, 0.966);
                border-radius: 28px 28px 28px 28px;
                font-size: -webkit-xxx-large;
            }
            .item-3
            {
                padding: 7px;
                grid-column-start: 2;
                grid-column-end: 4;
                font-size: x-large;
            }
            .item-4
            {
                padding: 7px;
                grid-column-start: 2;
                grid-column-end: 4;
                font-size: x-large;
            }
            .item-5
            {
                padding: 7px;
                grid-column-start: 2;
                grid-column-end: 4;
                font-size: x-large;
            }
            .item-6
            {
                padding: 7px;
                grid-column-start: 2;
                grid-column-end: 4; 
                font-size: x-large;
            }
            .item-7
            {
                grid-column-start: 1;
                grid-column-end: 4;
                background-color: rgb(33,99,255);
                border-radius: 5em;
                font-size: 38px;
                color: white;
                justify-self: stretch;
            }
            .item-box1
            {   
                padding: 10px;
                background-color: rgba(152, 173, 192, 0.966);
                grid-column: 1;
                grid-row: 2;
                border-radius: 17px 16px 17px 16px;
                height: 25px;
                width: 26px;
                justify-self: end;
            }
            .item-box2
            {   
                padding: 10px;
                background-color: rgba(152, 173, 192, 0.966);
                grid-column: 3;
                border-radius: 17px 16px 17px 16px;
                height: 25px;
                width: 26px;
                grid-column: 1;
                grid-row: 3;
                justify-self: end;
            }
            .item-box3
            {   
                padding: 10px;
                background-color: rgba(152, 173, 192, 0.966);
                grid-column: 3;
                border-radius: 17px 16px 17px 16px;
                height: 25px;
                width: 26px;
                grid-column: 1;
                grid-row: 4;
                justify-self: end;
            }
            .item-box4
            {   
                padding: 10px;
                background-color: rgba(152, 173, 192, 0.966);
                grid-column: 3;
                border-radius: 17px 16px 17px 16px;
                height: 25px;
                width: 26px;
                grid-column: 1;
                grid-row: 5;
                justify-self: end;
            }
        </style>
    </head>    
   <body>
        <section class="container">
            <div class="item-1">Ubication</div>
            <div class="item-2">></div> 
            <div class="item-3">Japan</div>
            <div class="item-4">Spain</div>
            <div class="item-5">Germany</div>
            <div class="item-6">Italy</div>
            <div class="item-7"><pre>         Lets Go!</pre></div>
            <div class="item-box1"></div>
            <div class="item-box2"></div>
            <div class="item-box3"></div>
            <div class="item-box4"></div>
        </section>
   </body>
</html>

se puede optimizar lineas guardando comandos que se repiten en otras variables.


# 🥕 Challenge CSS 11

CSS Grid: List

## 🥕 ¿En qué consiste?

La idea de este reto es que repliques el siguiente componente usando CSS Grid. En CSS Grid tenemos diferentes propiedades para los elementos padres y para los elementos hijos, por lo que la clave principal para resolver este reto es poder identificar qué elementos tenemos y que "rol" juegan, para así, identificar qué propiedades se le deben aplicar (recueda que hay hijos que también son padres).

<kbd>
<img width="300" src="https://i.ibb.co/5LgvDfx/Screen-Shot-2020-07-26-at-3-35-24-AM.png" />
</kbd>

> [Fuente de la imagen | Dribbble](https://dribbble.com/shots/9395928-Vuesax-4-0-Framework-Vue-js-Components/attachments)

Te dejo la siguiente documentación útil para resolver el reto:

* [CSS Grid Garden| Juego](https://cssgridgarden.com/#es)
* [A Complete Guide to Grid | CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Grid in CSS | CSS Reference](https://cssreference.io/css-grid/)
* [Learn CSS Grid](https://learncssgrid.com/)
* [Grid by Example](https://gridbyexample.com/examples/)

## 🥕 Pasos a seguir:

1. Hacer un "Fork" de este proyecto.
2. Revolver el reto.
3. Crear un Pull Request hacia este repositorio.

## 🥕 ¿Cómo contribuir?

Si quieres agregar o mejorar algo, te invito a colaborar directamente en este repositorio: [challenge-css-11](https://github.com/platzimaster/challenge-css-11/)

## 🥕 Licencia

challenge-CSS-11 se lanza bajo la licencia [MIT](https://opensource.org/licenses/MIT).
