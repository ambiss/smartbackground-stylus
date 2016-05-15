# smartbackground-stylus
Mixin para background inteligente, o mixin ao acessar a imagem que servirá a propriedade Background do CSS, não precisará das dimensões desta imagem, pois tais, virão pela engine do Stylus e configurará as propriedades width e height dinamicamente

#execute
div#page
    h2
      back('img/goomba.png', 'replacement')


#output
div#page h2 {
  background: url("img/goomba.png") no-repeat 0 0;
  width: 520px;
  height: 520px;
  text-indent: -9999em;
}

