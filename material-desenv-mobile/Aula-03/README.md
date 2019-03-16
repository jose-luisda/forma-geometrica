# Plataforma de Mobilidade Corporativa - (Aula 03)

## Introdução ao Bootstrap

Bootstrap é o mais popular framework `HTML`, `CSS`, e `JS` para desenvolvimento de projetos responsivo e focado para dispositivos móveis na web.
Documentação oficial
http://getbootstrap.com/

## Bootstrap
Aproposta do Bootstrap é "Crie projetos responsivos e móveis de primeira linha na web com a biblioteca de componentes de front-end mais popular do mundo".

O Bootstrap é um conjunto de ferramentas de código aberto para desenvolvimento com `HTML`, `CSS` e `JS`. Protótipo rapidamente de suas idéias ou crie seu aplicativo completo com nossas variáveis `Sass` e `mixins`, sistema de grade responsivo, extensos componentes pré-construídos e plugins poderosos criados no `jQuery`.

## Inicío rápido

Para iniciar você pode fazer o [Download](https://github.com/twbs/bootstrap/releases/download/v4.0.0-beta/bootstrap-4.0.0-beta-dist.zip) dos arquivos `CSS` e `JS` do Bootstrap além dos das bibliotecas [`JQuery`](https://code.jquery.com/jquery-3.2.1.slim.min.js) ([clique para saber mais sobre JQuery](https://jquery.com/)) e [`popper.js`](https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js) ([clique para saber mais sobre Popper.js](https://popper.js.org/index.html)) ou incluir os aquivos diretamente do repositório Bootstrap CDN.

### Exemplo de incusão direto pelo  Bootstrap CDN :
Copie e cole o `<link>` em seu `<head>` antes de todas as outras folhas de estilo para carregar no `CSS`.

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
```

Adicione os `JavaScript` opcionais, `jQuery` e `Popper.js`) perto do final de suas páginas, logo antes da tag `</ body>` de fechamento. Certifique-se de colocar `jQuery` e `Popper.js` primeiro, pois os nossos plugins `JavaScript` dependem deles.

```html
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>
```

### Exemplo de um tamplate inicial:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>
  </body>
</html>
```
## Sistema de Grid
Use sitema de grid de *mobile-first flexbox grid* para criar layouts de todas as formas e tamanhos, graças a um sistema de doze colunas, cinco níveis responsivos padrão, variáveis `Sass` e `mixins` e dezenas de classes predefinidas.

O sistema de grade da Bootstrap usa uma série de recipientes, linhas e colunas para layout e alinhamento de conteúdo. Abaixo está um exemplo.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div class="col">
          1 of 2
        </div>
        <div class="col">
          2 of 2
        </div>
      </div>
      <div class="row">
        <div class="col">
          1 of 3
        </div>
        <div class="col">
          2 of 3
        </div>
        <div class="col">
          3 of 3
        </div>
      </div>
    </div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>
  </body>
</html>
```

## Como o sistema de grade da Bootstrap funcionam em vários dispositivos.

|                             |Extra small <576px| Small ≥576px| Medium ≥768px| Large ≥992px  | Extra large ≥1200px |
|-----------------------------|------------------|-------------|--------------|-------------- |---------------------|
|Largura máxima do recipiente |None (auto)       |  540px    |720px       |960px        |1140px               |
|Class prefix                 |`.col-`           |  `.col-sm-` |`.col-md-`    | `.col-lg-`    |  `.col-xl-`         |
|Número de colunas            |12                |             |              |               |                     |

### Exemplo de layout com diversas grids:
```html
<!-- Stack the columns on mobile by making one full-width and the other half-width -->
<div class="row">
  <div class="col-12 col-md-8">.col-12 .col-md-8</div>
  <div class="col-6 col-md-4">.col-6 .col-md-4</div>
</div>

<!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
<div class="row">
  <div class="col-6 col-md-4">.col-6 .col-md-4</div>
  <div class="col-6 col-md-4">.col-6 .col-md-4</div>
  <div class="col-6 col-md-4">.col-6 .col-md-4</div>
</div>

<!-- Columns are always 50% wide, on mobile and desktop -->
<div class="row">
  <div class="col-6">.col-6</div>
  <div class="col-6">.col-6</div>
</div>
```

#### Continua na [aula 04](https://github.com/meta-sistemas-2017/plataforma-mobilidade/tree/master/Aula-04/Atividade).... :sweat_smile:

## [Atividade prática da aula 03](https://github.com/meta-sistemas-2017/plataforma-mobilidade/tree/master/Aula-03/Atividade)

# Referências - para saber mais...

 - https://getbootstrap.com/
 
[Voltar](https://github.com/meta-sistemas-2017/plataforma-mobilidade)