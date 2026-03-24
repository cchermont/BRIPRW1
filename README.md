# BRIPRW1
IFSP - Programação pra Web 1

## Sistema de Cadastro e Gerenciamento de Pássaros

Este projeto é um mini-sistema web responsivo para cadastro e gerenciamento de pássaros, desenvolvido utilizando Bootstrap. O sistema permite cadastrar novas aves com nome popular, nome científico, região e observações, além de listar, visualizar detalhes e acessar um dashboard com estatísticas.

### Estrutura do Projeto

- index.html: Página inicial (Home)
- cadastro.html: Página de cadastro de pássaros
- listagem.html: Página de listagem de pássaros cadastrados
- dashboard.html: Painel com estatísticas
- detalhes.html: Página de detalhes de um pássaro específico

*Sugestão de estrutura de pastas:* Para este projeto simples, manter todos os arquivos HTML na raiz é suficiente. Se o projeto crescer, considere criar pastas como css/, js/ e assets/ para organização.

### Componentes Bootstrap Utilizados

O sistema utiliza os seguintes componentes Bootstrap:

1. *Navbar*: Barra de navegação presente em todas as páginas, com links funcionais para navegação entre as seções.
   - Aparece em: Todas as páginas (index.html, cadastro.html, listagem.html, dashboard.html, detalhes.html)

2. *Formulário*: Formulário de cadastro com inputs de texto, select e textarea.
   - Aparece em: cadastro.html

3. *Tabela*: Tabela para listagem de pássaros com cabeçalho e corpo.
   - Aparece em: listagem.html

4. *Modal*: Modal para confirmação de cadastro e para exibir detalhes dos pássaros.
   - Aparece em: cadastro.html (confirmação), listagem.html (detalhes)

5. *Card*: Cards para exibir informações resumidas e detalhes.
   - Aparece em: index.html (card sobre o sistema), dashboard.html (cards de estatísticas), detalhes.html (card com informações do pássaro)

6. *Alert*: Alerta informativo.
   - Aparece em: index.html (dica sobre regiões)

### Responsividade

A responsividade foi aplicada utilizando as classes de grid do Bootstrap:

- *Container*: .container ou .container-fluid em todas as páginas para centralizar o conteúdo.
- *Row e Col*: Utilização de .row e .col-* (como .col-12, .col-md-6, .col-md-4) para layout responsivo.
- *Navbar*: Navbar responsiva com .navbar-toggler para dispositivos móveis.
- *Cards no Dashboard*: Grid responsivo com .col-md-4 para 3 colunas em desktop e empilhamento em mobile.

O sistema é totalmente responsivo, adaptando-se a dispositivos móveis, tablets e desktops.

### Como Executar

Abra qualquer arquivo HTML em um navegador web. Não há necessidade de servidor backend, pois os dados são fictícios e estáticos.

### Requisitos Atendidos

- [x] Pelo menos 5 páginas HTML
- [x] Uso obrigatório de Bootstrap
- [x] Navbar idêntica e funcional em todas as páginas
- [x] Estrutura com .container, .row, .col-*
- [x] Responsividade garantida
- [x] Formulário com inputs corretos e modal de confirmação
- [x] Tabela com 5+ registros fictícios e ações (detalhes modal, excluir alert)
- [x] Dashboard com 3+ cards e ícones
- [x] Página de detalhes com card
- [x] Uso de pelo menos 6 componentes Bootstrap
- [x] Código limpo, reutilização de componentes, HTML5 semântico
- [x] Bootstrap via CDN
- [x] Dados fictícios (sem backend)