<h1>Comandos para rodar no docker:</h1>
<ol>
  <li>Criar imagem: docker build -t {nome do projeto} .</li>
  <li>Rodar imagem: docker run 8080:8080 {nome da imagem} </li>
</ol>
<p>Obs: O docker é inicializado dessa forma (colocando as portas) porque é com um servidor. Caso seja pagina web pode apenas colocar docker run e o nome do projeto.</p>
