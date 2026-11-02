**Soleil Perfumes**

Integrantes
Aimée Débora Rafaele Santos Lucena 
Anny Luyrara Medeiros Freire 
Mariluz Pereira Silva 

**Tema do projeto**

O projeto Soleil Perfumes é uma página web de catálogo de perfumes. A proposta é apresentar diferentes fragrâncias de forma organizada e visualmente agradável, mostrando a imagem, o nome, o tamanho e o preço de cada produto.

**Tipo de layout**

O tipo de layout escolhido foi Catálogo, pois a página apresenta uma lista de produtos organizados em cards.

**Objetivo da página**

O objetivo da página é criar uma interface simples para apresentar os perfumes da Soleil Perfumes. A página utiliza HTML e CSS separados, componentes reutilizáveis, padrão BEM e Flexbox para organizar os elementos.

**Componentes simples**

Os principais componentes simples utilizados no projeto são:

- Cabeçalho
- Links de navegação
- Imagens dos produtos
- Títulos
- Preços
- Botões

**Componentes compostos**

Os principais componentes compostos são:

Card de produto
O card reúne vários elementos, como imagem, título, preço e botão de detalhes.

Cabeçalho
O cabeçalho é composto pelo nome da marca e pelos links de navegação da página.

**Padrão BEM**

O projeto utiliza o padrão BEM para organizar e nomear as classes do CSS.

Alguns exemplos utilizados são:
- ".card" — bloco principal do card.
- ".card__img" — imagem do card.
- ".card__titulo" — título do produto.
- ".card__preco" — preço do produto.
- ".card__botao" — botão do card.
- ".card--escuro" — variante escura do card.
- ".card__titulo--escuro" — variante do título.
- ".card__preco--escuro" — variante do preço.
- ".card__botao--escuro" — variante do botão.
- ".header__titulo" — título do cabeçalho.
- ".header__item" — itens de navegação.

**Uso de Flexbox**

O Flexbox foi utilizado principalmente no cabeçalho e no container dos produtos.

No cabeçalho:

header {
    display: flex;
}

No container dos cards:

.container {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    gap: 10%;
}

O "flex-wrap" permite que os cards sejam distribuídos em mais de uma linha, enquanto o "gap" cria espaçamento entre eles.

**Variantes visuais**

O projeto possui uma variante visual dos cards, representada pelo componente ".card--escuro".

A versão normal utiliza cores claras, enquanto a versão escura utiliza um fundo marrom mais escuro e cores diferentes para os textos e botões.

Também foram criados estados ":hover" para os links e botões, proporcionando uma mudança visual quando o usuário passa o mouse sobre eles.

**Tecnologias utilizadas**

- HTML5
- CSS3
- Flexbox
- Padrão BEM
