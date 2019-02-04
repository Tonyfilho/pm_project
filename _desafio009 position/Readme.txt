
                                           
                                           
                                           
                                          posição

De forma a criar layouts mais complexos, precisamos discutir a propriedade position. Têm um grupo de valores possíveis, e os seus nomes não fazem sentido e são impossíveis de recordar. Vamos lá passar por eles um a um, talvez devas guardar esta página também.

                                         static
                                         


                                         fixed
<div class="fixed">
Hello! Don't pay attention to me yet.

</div>
Um elemento fixo é posicionado relativamente ao viewport, significa que fica sempre no mesmo sitio, mesmo que faça scroll da página. Com relative, são utilizadas as propriedades top, right, bottom, e left.

Tenho a certeza que notaste o elemento fixo no canto inferior direito da página. Estou a dar-te permissão para lhe dares atenção agora. Aqui está o CSS que o coloca lá:


Um elemento fixo não deixa espaço na página onde estaria normalment localizado.

Browsers de dispositivos móveis têm um apoio instável para fixar. Aprender aqui mais sobre a situação.


                                          absolute

absolute é o valor de posicionamento mais complicado. absolute comporta-se como fixed só que relativo ao posicionamento do antecessor mais próximo em vez de relativo ao viewport. Se um elemento positionado absolutamente não tem um antecessor posicionado, utiliza o corpo do documento, e continua a mover-se igualmente com o scroll da página. Lembra-te, um elemtno "posicionado" é aquele em que a posição é tudo excepto static.

Aqui está um exemplo simples:


Estas coisas são complicadas, mas é essencial para criar grandes layouts com CSS. Na próxima página vamos utilizar position num exemplo mais prático.


