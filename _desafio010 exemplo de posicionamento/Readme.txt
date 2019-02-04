
                                           
                                           
                                           
                                         exemplo de posicionamento
Esta coisa do posicionamento pode fazer um pouco mais de sentido num exemplo prático. Por baixo está um layout realista de uma página.

Este exemplo funciona porque o recipiente é mais alto que a nav. Caso não fosse, a nav iria transbordar para fora of do seu recipiente. Nas próximas páginas vamos discutir outras técnicas de layout the têm diferentes prós e contras.


OBS: Se utilizas um cabeçalho fixo ou rodapé, assegura-te que existe espaço para o mesmo! Eu coloco uma margin-bottom no body.


                         exemplo de configuração do CSS  agradável onde se minimiza ou redimenciona a pagina e ela se comporta bem:

 .container {
  position: relative;
}
nav {
  position: absolute;
  left: 0px;
  width: 200px;
}
section {
  /* position is static by default */
  margin-left: 200px;
}
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  height: 70px;
  background-color: white;
  width: 100%;
}
body {
  margin-bottom: 120px;
}