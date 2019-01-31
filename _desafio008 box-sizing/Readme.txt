
                                           
                                           
                                           
                                           box-sizing


Após gerações, as pessoas aperceberam-se que a matemática não é divertida, então foi criada uma nova propriedade de CSS chamada box-sizing. Quando configuras box-sizing: border-box; num elemento, o espaçamento e fronteira desse elemento deixa de aumentar a sua largura. Aqui está o mesmo elemento da página anterior, mas com box-sizing: border-box; em ambos os elementos:


Uma vez que isto é muito melhor, alguns autores queriam que todos os elementos em todas as suas páginas funcionassem sempre desta maneira. Esses autores colocam o seguinte CSS nas suas páginas:

* {
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}

Isto assegura que todos os elementos são sempre dimensionados desta maneira mais intuitiva.

Uma vez que box-sizing é bastante novo, deves utilizar por agora os prefixos -webkit- e -moz-, como eu tenho nestes exemplos. Esta técnica permite activar características experimentais em browsers expecificos. Mantém também em mente que isto é IE8+.