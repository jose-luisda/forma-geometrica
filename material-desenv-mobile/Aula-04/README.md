# Plataforma de Mobilidade Corporativa - (Aula 04)

## Componentes do Bootstrap

O Bootstrap tem dezenas de componentes reutilizáveis criados para fornecer elementos dropdown, grupos de inputs , navegação com tabs, alertas e muito mais.
para acesso todos os componentes do bootstrap acesse: https://getbootstrap.com/docs/4.0/components/alerts/

### Alerts (Alertas)

Os componentes de Alerts, oferecem um alerta personalizado, para mensagens de feedback de ações de usuários.

#### Exemplo:
```html
<div class="alert alert-primary" role="alert">
  This is a primary alert—check it out!
</div>
<div class="alert alert-secondary" role="alert">
  This is a secondary alert—check it out!
</div>
<div class="alert alert-success" role="alert">
  This is a success alert—check it out!
</div>
<div class="alert alert-danger" role="alert">
  This is a danger alert—check it out!
</div>
<div class="alert alert-warning" role="alert">
  This is a warning alert—check it out!
</div>
<div class="alert alert-info" role="alert">
  This is a info alert—check it out!
</div>
<div class="alert alert-light" role="alert">
  This is a light alert—check it out!
</div>
<div class="alert alert-dark" role="alert">
  This is a dark alert—check it out!
</div>
```
Utilizando as classes `.alert` para definir um elemento como alerta, somado ao tipo de alerta por exemplo: `class="alert alert-primary"`, cria uma caixa de alerta de cor azul.

#### Alerta com botão de fechar

Se você incluir os js da `JQuery` e os js do `Boostrap`, você pode usar um alerta com botão de fechamento automático.

#### Exemplo:
```html
<div class="alert alert-warning alert-dismissible fade show" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close">
    <span aria-hidden="true">&times;</span>
  </button>
  <strong>Holy guacamole!</strong> You should check in on some of those fields below.
</div>
```
Para mais formas de alerta acesse : https://getbootstrap.com/docs/4.0/components/alerts/

### Buttons (Botões) e Button group (Grupo de botões)

O boostrap lhe oferece uma variedade de botões personalizados de tamanhos e cores diferentes para seu site.

#### Exemplo de botões

```html
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-light">Light</button>
<button type="button" class="btn btn-dark">Dark</button>
<button type="button" class="btn btn-link">Link</button>
```
Utilizando a classe `.btn` em elemento você o define como um botão, e somando a uma classe que define o tipo de botão por exemplo: `class="btn btn-primery"` você cria um botão personalizado na cor azul.
Para saber mais sobre os botões no bootstrap acesse: https://getbootstrap.com/docs/4.0/components/buttons/

Além de tilizar botões de forma separada você também pode utilizar grupos de botões:

#### Exemplo de grup de botões

```html
<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-secondary">Left</button>
  <button type="button" class="btn btn-secondary">Middle</button>
  <button type="button" class="btn btn-secondary">Right</button>
</div>
```
Basta adicionar a classe de `.btn-group` au um elemento em bloco e adicionar os botões dentro de sua abertura e fechamento, assim você tera os botões agrupados como no exemplo acima.
Para saber mais sobre o grupos de botões acesse: https://getbootstrap.com/docs/4.0/components/button-group/

### Carousel (Carrossel)

Um componente de apresentação de slides rotativo através de elementos como imagens ou slides de texto.
Para mais formas de Carrossel acesse : https://getbootstrap.com/docs/4.0/components/carousel/

#### Exemplo de Carrossel

```html
<div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="..." alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="..." alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="..." alt="Third slide">
    </div>
  </div>
</div>
```
Basta usar a estrutura basica para o carrossel classes `.carousel` e `.slide`, e dentro inserir uma estrutura interna com a classe `.carousel-inner`, e dentro da estrutura interna inserir os itens (`.carousel-item`) do carrosseu com suas imagens (`<img>`).

### Forms (Formulários)

O Bootstrap oferece vários estilos pré-definidos para estilizar o formulários html.

#### Exemplo de Formulário

```html
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <div class="form-check">
    <label class="form-check-label">
      <input type="checkbox" class="form-check-input">
      Check me out
    </label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

Para saber mais sobre os formulários acesse: https://getbootstrap.com/docs/4.0/components/forms/
e sobre input group (Grupo de input) acesse: https://getbootstrap.com/docs/4.0/components/input-group/

### Modal

Ao utilizar plugin JavaScript de Modal para adicionar dialogos em seu site com lightboxe, usar como notificação outros.

#### Exemplo de Modal

```html
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```

**Aviso!:** Importante lembrar que para uso desse recurso além de adicionar o `js` do bootstrap você deve adicionar as bibliotecas js: `JQuery` e `pooper.js`.
Para saber mais sobre as formas de uso do componente de modal acesse: https://getbootstrap.com/docs/4.0/components/modal/

### Navbar (Barra de navegação)

O bootstrap oferece uma estruta padrão para barra de navegação responsiva.

#### Exemplo de Barra de navegação responsiva

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
```

**Aviso!:** Importante lembrar que para uso da responsividade dos itens da barra de navagação além de adicionar o `js` do bootstrap você deve adicionar as bibliotecas js: `JQuery` e `pooper.js`.
Para saber mais sobre as formas de uso do componente de modal acesse: https://getbootstrap.com/docs/4.0/components/navbar/

    Esses são só alguns dos componentes que o Bootstrap oferece para melhorar ainda mais seus layout fique a vontade de ler a documentação e testar os outros de forma bem simples. :+1:

---

### Tables (Tabelas)

Apesar de não fazer parte da categoria de componentes e sim de content (Conteúdo), o bootstrap também oferece estilos pré-definidos para suas tabelas.

```html
<table class="table table-striped table-hover table-bordered">
  <thead>
    <tr>
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Username</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```

Você pode utilizar a classe `.table` para já deixar um estilo mais bonito em sua tabela, além de poder combinar com classes como: `.table-striped`, que adiciona o efeito zebrado em suas tabelas, `.table-hover` que adiciona um efeito de mudança de cor das linhas da tabala ao passar o curso sobre elas e `.table-bordered` que adiciona borda em sua tabela.
Para saber mais sobre Tabelas acesse: https://getbootstrap.com/docs/4.0/content/tables/

E para saber mais sobre os recursos do grupo de **Contents** do bootstrap, como estilizar imagens, a tipografia padrão dos estilos entre outros acesse: https://getbootstrap.com/docs/4.0/content/reboot/

### Conclusões

O uso do framework boostrap é muito simples, isso se dá pelo fato de sua documentação ser muito abrangente e intuitiva com exemplos apenas para você copiar e colar, o que pode ser mais complicado de inicío é entender seu sistema de grid, mas ao dominar esse conceito, e ter um conhecimento prévio de `HTML`, `CSS` e `Javascript`, você consegue usar qualquer recurso so framework sem qualquer problemas.

### Outros frameworks front-end que trabalham com design responsivo.

Além do mais popular deles que é o [Boostrap](https://getbootstrap.com/), existem outros frameworks muitos bons que além de trabalhar com a mesma idéia de sistema de grids, componentes e outros, e trazem uma boa documentação.
São alguns deles:

- [Bulma](http://bulma.io/):  (ps. Não a Bulma do Dragon Ball :stuck_out_tongue_winking_eye:) Esse framework  é muito semelhante ao Boostrap, além de trazer o sistema de grids e componentes similares, o Bulma lhe dá alternativa diferentes as estilos padrões do Bootrap (ps. Particulamente eu não sou muito fã do verde que eles adotam como base para seus layout :sleepy:)
- [Materialize](http://materializecss.com/): Esse cara é muito bom por trazer além de todo os conceitos de grids e componentes, ele tenta seguir os padrões de layout sugeridos pela Google (É sabe a Google? Aquela que vai dominar o mundo? Pois é, essa mesma :v:). Que é os conceitos do [Material Design](https://material.io/guidelines/material-design/introduction.html) (que veremos em aulas futuras), Materialize está para lançar sua nova versão, aguardem. :sunglasses:

Temos também, o [Framework7](http://framework7.io/), mas esse é muito mais voltado para se criar design de aplicativos com `HTML`, `CSS` e `JavaScript`, do que design responsivo. o mesmo conta com muito mais recurso que o Bootstrap.

### Layouts e tamplates prontos que utilizem bootstrap.

(Esse você quer saber né?? doido(a) para sair baixando layout pronto por ai :weary:)

- [Start Bootstrap](https://startbootstrap.com/): Esse site oferece inúmeros tamplates prontos, porém como o Bootstrap 4 acabou de ser lançado, a maioria (acho até que todos :cry:) dos template estão na sua versão 3.
- [AdminLTE](https://adminlte.io/themes/AdminLTE/index2.html): Esse é para mim o melhor e mais completo template **GRÁTIS** (isso mesmo de grátis!!!!!!!!!!!!! :scream::scream::scream::scream:) para áreas administravas de sites e até mesmo sistemas, so que infelizmente esse carinha ainda está em bootstrap 3 :sob:.
- [AdminBSB](https://gurayyarar.github.io/AdminBSBMaterialDesign/index.html): (Esse template é lindo! :heart_eyes:) Assim como o [AdminLTE](https://adminlte.io/themes/AdminLTE/index2.html) também é voltado para áreas administravas de sites e até mesmo sistemas, porém o mesmo não é feito em Boostrap e sim em [Materialize](http://materializecss.com/), ou seja ele aplica todos os conceitos do [Material Design](https://material.io/guidelines/material-design/introduction.html).

#### Até a próxima aula! :sweat_smile:

## [Atividade prática da aula 04](https://github.com/ptsilva/plataforma-mobilidade/tree/master/Aula-04/Atividade)

# Referências - para saber mais...

 - https://getbootstrap.com/
 - http://bulma.io/
 - http://materializecss.com/
 - http://framework7.io/
 - https://startbootstrap.com/
 - https://adminlte.io/themes/AdminLTE/index2.html
 - https://gurayyarar.github.io/AdminBSBMaterialDesign/index.html
 
[Voltar](https://github.com/ptsilva/plataforma-mobilidade)