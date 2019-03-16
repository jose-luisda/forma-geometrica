# Plataforma de Mobilidade Corporativa - (Aula 02)

[Clique para baixar o Slide da Aula 02](https://github.com/meta-sistemas-2017/plataforma-mobilidade/blob/master/Aula-02/PLATAFORMA%20DE%20MOBILIDADE%20CORPORATIVA%20-%20Aula%2002%20-%202017.2.pdf)

## Web App

Como vimos anteriormente os  **Web App não é um aplicativo real** e não estará disponível nas App Stores. Na verdade é um site desenvolvido exclusivamente para dispositivos móveis. Possui uma programação que reconhece que o usuário está acessando por um smartphone e se adapta a ele.

Em 2014, 9,4% de todas as compras online foram realizadas em dispositivos móveis, segundo o relatório WebShoppers divulgado pela [E-bit](http://www.ebit.com.br/empresa) no começo do ano de 2016. O crescimento do m-commerce (o e-commerce mobile) entre 2013 e 2014 chegou a 84%, e a tendência é de que esses indicadores continuem aumentando nos próximos anos.

Por isso é que vender na internet, hoje, inclui necessariamente uma preocupação com os usuários de tablets e smartphones. Afinal, em países como os EUA, já são feitas mais buscas online nesse tipo de dispositivos do que em computadores desktops, criando um novo conceito de desenvolvimento.

## Mobile first!

Esse conceito inverte a metodologia clássica de desenvolvimento web, considerando que quando vamos começar a desenvolver e planejar projetos virtuais, desde um pequeno site até um grande sistema, primeiramente devemos pensar no comportamento em dispositivos móveis e somente depois em desktops ou notebooks.

Mas como vender de maneira eficiente para todos os públicos? Como estar presente com boa usabilidade e comunicabilidade, independentemente do formato e do tamanho da tela? As respostas estão ambas no **design responsivo**.

## O que é design responsivo

Há algum tempo, a maioria dos computadores utilizava um monitor de resolução 800×600 ou 1024×768 pixels. Para os sites, a dimensão das telas não representava muito no que se referia à usabilidade e à navegação de suas interfaces. Mas hoje em dia temos não só uma infinidade de resoluções e proporções de telas de computadores, mas também dispositivos móveis, como Smart TVs, tablets e smartphones com tamanhos e resoluções diversas. E essa variedade gera um grande impacto na qualidade da experiência do usuário.

Nesse contexto, um site é considerado responsivo quando **possui a capacidade de ajustar a disposição de seus componentes visuais, adaptando-se à resolução de tela na qual é exibido — alterando posição, altura, largura e até mesmo a formatação dos elementos gráficos —, a fim de garantir a melhor experiência do usuário ao navegar por suas páginas**.

O design responsivo é uma ótima solução na hora de resolver problemas de multi-telas, mas resolver isso a partir da perspectiva de impressões é um pouco ma partir do momento que a tela do dispositivo diminui de tamanho, o conteúdo também começa a preencher um espaço mais vertical, onde tudo que está abaixo é “empurrado” também para baixo. Esse processo é chamado de fluxo.

Talvez seja um pouco complicado de entender caso você esteja acostumado a projetar sites com pixels e pontos, mas logo fará todo o sentido, assim que você se acostumar com o processo.ais difícil. Não há nenhum tamanho fixo das páginas, nem milímetros, centímetros e muito menos nenhum tipo de restrição física que precisa ser resolvida. Projetar um site através de pixels para desktop ou Mobile também já é passado, principalmente à medida que novos gadgets surgem e te permitem abrir um site, por exemplo.

Portanto, é preciso esclarecermos alguns princípios básicos a respeito do web design responsivo a fim de consolidar todo o conceito ao invés de ir contra a maré.

## Design Responsivo X Adaptativo

O objetivo de ambos é o mesmo: facilitar a navegação do usuário em diferentes plataformas de acesso, independente de onde é feito, tanto por PC’s quanto por dispositivo mobile. Porém, existe muita confusão entre esses termos: quando usar? Qual usar? Ambos têm muito em comum, e essa confusão toda é normal. Basicamente, o design Adaptativo nada mais é que uma variação do design responsivo, a diferença é que o Adaptativo se adapta a telas de tamanhos específicos, enquanto o Responsivo adapta todo o conteúdo.

## O Fluxo

A partir do momento que a tela do dispositivo diminui de tamanho, o conteúdo também começa a preencher um espaço mais vertical, onde tudo que está abaixo é “**empurrado**” também para baixo. Esse processo é chamado de fluxo.

Talvez seja um pouco complicado de entender caso você esteja acostumado a projetar sites com pixels e pontos, mas logo fará todo o sentido, assim que você se acostumar com o processo.

## Unidades Relativas

Imagine que a tela possa ser um desktop, tela de smartphone ou qualquer coisa que atinja o meio termo entre as duas. A densidade dos pixels também pode variar e é por isso que também precisamos de unidades flexíveis e que funcionem em qualquer lugar.

É aí que as unidades relativas baseadas em porcentagens vem a calhar. Assim, fazer algo na escala de 50% significa que ele sempre ocupará a metade da tela (ou da janela de exibição, que é o tamanho da janela do navegador aberta).

## Pontos de Interrupção

Os pontos de interrupção permitem que o layout mude em pontos pré definidos, ou seja: ter 3 colunas em um desktop, mas apenas uma coluna em dispositivos móveis, por exemplo. A maioria das propriedades CSS podem ser alteradas de um ponto de interrupção para outro.

Normalmente, onde se coloca um desses pontos dependerá primeiramente do tipo de conteúdo que está ali. Se ocorrer de uma sequência se quebrar, talvez seja necessário adicionar um ponto de interrupção.

Mas certifique-se de usá-los com cuidado. É possível que tudo vire uma grande bagunça rapidamente caso você não entenda o que está influenciando o quê.

## Valores Mínimos e Valores Máximos

Às vezes é ótimo que o conteúdo ocupe toda a largura de uma tela, assim como funciona nos dispositivos móveis, por exemplo. Mas ter esse mesmo conteúdo se estendendo por toda a largura da tela de uma TV pode simplesmente não fazer sentido.

É por isso que os valores mínimos e máximos ajudam bastante. Por exemplo, uma largura de 100% com máxima largura de 1000 pixels significaria que o conteúdo irá preencher toda a tela, mas nunca ultrapassando a marca de 1000 pixels.

## Objetos Aninhados

Você se lembra da posição relativa? É muito difícil apenas ter um monte de elementos dependendo uns dos outros, pois isso seria difícil de controlar. Portanto, manter os elementos bem envolvidos e únicos os deixaria mais compreensíveis, limpos e muito mais bem-arrumados.

É ai que as unidades estáticas como os pixels podem ajudar. Eles são bastante úteis para aquele tipo de conteúdo que você não quer manter em escala, como logos e botões, por exemplo.

## Desktop ou Mobile – Qual vem primeiro?

Tecnicamente não existe uma real diferença se o projeto é iniciado a partir de uma tela menor para uma tela maior ou vice-versa. No entanto, existem algumas limitações caso você decida começar pelo Mobile, mas que poderão ser bastante úteis na hora de algumas tomadas de decisão.

Muitas vezes as pessoas até mesmo começam de ambas as extremidades (mobile e desktop simultaneamente). É ai que você precisa decidir o que melhor funcionam para você a fim de obter a máxima dos dois.

## Quero fazer o meu site responsivo. Por onde é melhor começar?

A verdade é que você provavelmente precisará reconstruir boa parte do seu site. Mas para ter um pouco menos de trabalho, recomendo que procure utilizar frameworks que já trabalhem com o design responsivo. Frameworks são estruturas de código já prontas que trazem consigo diversas linhas em CSS, JavaScript e HTML já escritas, facilitando bastante o trabalho do desenvolvedor do site.

##### O framework que iremos utilizar será o [Bootstrap](http://getbootstrap.com/)

# Referências - para saber mais...

 - http://marketingdeconteudo.com/web-design-responsivo/
 - https://moip.com.br/blog/design-responsivo-por-que-voce-precisa-saber/
 - https://aldabra.com.br/artigo/design-responsivo-sites
 - http://www.midiatismo.com.br/design-responsivo-entenda-o-que-e-a-tecnica-e-como-ela-funciona
 - http://k2comunicacao.com.br/blogs/design-responsivo-x-design-adaptativo/
 - http://www.ogilvy.com.br/files/mobile.pdf
 
[Voltar](https://github.com/meta-sistemas-2017/plataforma-mobilidade)