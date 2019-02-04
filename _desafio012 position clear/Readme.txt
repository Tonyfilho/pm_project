
                                           
                                           
                                           
                                         exemplo de clear


    
clear
A propriedade clear é importante para controlar o comportamento dos flutuadores. Compare estes dois exemplos:

<div class="box">...</div>
<section>...</section>
.box {
  float: left;
  width: 200px;
  height: 100px;
  margin: 1em;
}
<div class="box">
Sinto que estou a flutuar!

</div>
<section>
Neste caso, o elemento section está actualmente depois de div. Contudo, desde que div flutua para esquerda, o que acontece é isto: o texto na section flutua á volta da div e a section envolve tudo o resto. Então e se quisessemos que a section aparecesse mesmo depois do elemento flutuado?

</section>
.box {
  float: left;
  width: 200px;
  height: 100px;
  margin: 1em;
}
.after-box {
  clear: left;
}
<div class="box">
Sinto que estou a flutuar!

</div>
<section class="after-box">
Utilizando clear movemos agora esta secção para debaixo do elemento flutuado div. Utilizas o valor left para limpar elementos flutuados para a esquerda. Podes também limpar com right e both.

</section>
Anterior Próximo