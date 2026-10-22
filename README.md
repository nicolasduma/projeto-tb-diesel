# Projeto TruckStar

Este projeto é o site da TB Diesel. Atualmente, ele contém as páginas e a parte visual do site, feitas com HTML, CSS e JavaScript. O back-end será desenvolvido depois.

## Páginas

- **`index.html`** — Página inicial. Apresenta o carrossel, serviços, guincho, produtos, informações sobre a empresa e alguns posts do blog.
- **`services.html`** — Lista os serviços oferecidos pela oficina.
- **`products.html`** — Apresenta os produtos.
- **`blog.html`** — Mostra a lista de posts do blog.
- **`post.html`** — Exibe o conteúdo de um post. Por enquanto, apresenta um exemplo fixo.
- **`create-post.html`** — Tela administrativa para preencher os dados de um post e ver uma prévia antes de publicar.
- **`manage-posts.html`** — Tela administrativa com exemplos de posts e botões para editar ou excluir.

## Arquivos de estilo

- **`global-style.css`** — Estilos compartilhados pelo site, como cores, cabeçalho, navegação, carrossel, cartões, rodapé e adaptações para telas menores.
- **`admin-pages.css`** — Estilos compartilhados pelas páginas administrativas.
- **`create-post.css`** — Estilos do formulário de criação e da prévia do post.
- **`manage-posts.css`** — Estilos da lista de posts na área administrativa.
- **`post.css`** — Estilos do conteúdo individual de um post.
- **`products.css`** — Ajustes de exibição dos produtos em telas menores.

## Imagens e fontes

- **`images/`** — Imagens usadas no site, incluindo logo, imagens do carrossel, produtos, guincho e ícones SVG do menu e do carrossel.
- **`fonts/`** — Arquivos locais da fonte Inter Tight, em versões normal e itálica.

## O que já funciona no navegador

- O menu se adapta a telas menores e pode ser aberto ou fechado.
- O carrossel troca de imagem automaticamente e permite navegar pelas setas ou pelos botões de cada slide.
- O formulário administrativo permite preencher os dados, validar alguns campos e gerar uma prévia do post.
- A prévia pode mostrar a imagem selecionada e um vídeo do YouTube.

## O que será desenvolvido no back-end

As telas administrativas ainda usam exemplos e não salvam posts de verdade. Quando o back-end for integrado, ele deverá permitir:

- Salvar, listar, editar e excluir posts.
- Exibir no blog e nas páginas de post os conteúdos salvos, em vez dos exemplos fixos.
- Receber e guardar as imagens enviadas com os posts.
- Proteger a área administrativa para que apenas pessoas autorizadas possam gerenciar o conteúdo.
- Validar os dados também no servidor antes de salvar.

O envio do formulário ainda não publica o post. A prévia é apenas local, no navegador. A tecnologia e a forma de armazenamento do back-end serão definidas durante o desenvolvimento dessa parte.

## Testar projeto

Acesse o link: https://tb-diesel.netlify.app/
