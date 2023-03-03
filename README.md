# README.md

Este documento sinala os obxectivos e as fases do proxecto "Elementos repetidos"

* Creación: 16/01/23
* Tecnoloxías: html/css
* Editor: sublimetext
* reset.css : https://meyerweb.com/eric/tools/css/reset/reset.css (deberá facerse a chamada o mesmos antes da nosa folla de estilos)
* Iconos: https://fontawesome.com/
* Fontes: www.fonts.google.com Montserrat, Roboto Slab (100 400 700)


## OBXETIVOS
A páxina conta con tres cards nas que se mostrará un imaxe de fondo, unha imaxe do perfil sobreposta, o nome e a profesión, unha brebe descripción, e os enlaces as súas redes sociais.	


## FASES
1. Creación da estructura do HTML.
2. Definimos os correspondentes formatos a container, cards-wrapper e card.
3. Damos formato tanto a imaxe do fondo na card (profile-image), como na imaxe do perfil (proile-image), tamén o facemos para o contido e máis o botón. Para este último, crearemos tamén unha animación, empregaremos unha transformación, que se iniciará en intervalos de o escalado que terá e diferentes rotacións en Z tanto positivas como negativas, para simular que o botón se move sobre ese eixe.
4. Estableceranse o estilo para os (social-icons), que se chamarán dende o html empregado fons-awesome, así como un escalado o facer hover sobre eles
5. Definiremos os @keyframes para a animación da card, de xeito que vaian aparecendo una a continuación da outra recreando un efecto de fundido, establecendo que partan dunha opacidade 0 o inicio ata unha opacidade 1 o completarse, así como a duración da animación e o retardo para cada card.
6. Daremos formato o heading, para o texto que crearemos dende JavaScript.
7. Creación efecto texto letra a letra. Para elo empregaremos un script de JavaScript, que chamaremos dende o HTML:
    - Declararemos unha constante "heading" que almacenará o texto que queremos que se mostre.
    - Declararemos una variable let, para establecer i en cero.
    - Declararemos una constante que será igual a una función que denominaremos typing, na que mentres i sexa menor o largo da constante heading, chamará a clase(document.querySelector) .heading e dentro crearase un html que representará o primeiro caracter da cosntante heading, e sumara 1 o valor de i. isto repetirase caracter a carcter ata que o valor de i sexa igual o largo da constante heading. Daremoslle un tempo para levar a cabo a función (setTimeour).
    - Por último executaremos a función typing
8. Para rematar ocuparemos a reponsabilidade, establecendo os diferentes media queries para que se adapte os formatos movil, tablet e pc.