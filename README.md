# Curso_Bootstrap4
Curso Bootstrap4 - Udemy

* browser-sync: cmd > browser-sync start --server --files "*.html"

## script bootstrap <br>

< head> <br> < link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous"> <br> </ head> <br>

< body>  
< script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></ script> <br>
< script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.5/dist/umd/popper.min.js" integrity="sha384-Xe+8cL9oJa6tN/veChSP7q+mnSPaj5Bcu9mPX5F5xIGE0DVittaqT5lorf0EI7Vk" crossorigin="anonymous"></ script> <br>
< script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.min.js" integrity="sha384-kjU+l4N0Yf4ZOJErLsIcvOU2qSb74wXpOhqTvwVx3OElZRweTnQ6d31fXEoRD1Jy" crossorigin="anonymous"></ script> <br>
< / body>

## Container

.container { cria container adaptavel com margem centralizada. declarasse " .container " e VSCODE cria uma div com a classe instanciada } <br>

.container-fluid { cria um container sem margem }

## Mobile First

* Responsive Breakpoint: <br>
O CSS é focado por padrão na largura máxima de 576 pixels e o bootstrap se refere a esse tamanho com a sigla <strong>xs</strong>. <br>
Acima desse tamanho temos a largura mínima de 576 pixels nomeada sm. <br>
Após o tamanho sm temos a largura mínima de 768 pixels nomeada md. <br>
Depois de sm temos a largura mínima de 992 pixels nomeada lg. <br>
Por fim temos a largura mínima de 1200 pixels nomeada xl. <br>

# Grid System

* Foco inicial é para dispositivos moveis! 

* grid padrão é 12 columns <br>
Distribuidas por classe: .col-12 (informa quantas colunas) <br>
< header class="col-12"> <br>

* Para desempenhar o alinhamento das colunas, toda div deve estar dentro de um container: .container <br>
* .row auxilia nos padding, todo row deve estar dentro de um container. <br>

* Todo "conteiner" tem  ".row " e todo ".row" tem um ".col-..." 

