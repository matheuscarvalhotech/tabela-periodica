# Tabela Periódica Interativa

> Tabela periódica interativa desenvolvida como projeto acadêmico de front-end, com foco em estruturação de layouts, CSS Grid e interatividade com JavaScript.

---

## Visão Geral

O projeto apresenta uma representação visual da **Tabela Periódica dos Elementos**, permitindo consultar informações de cada elemento diretamente pela interface.

## Os elementos são organizados de acordo com sua posição na tabela periódica e diferenciados visualmente por categorias. Ao passar o mouse sobre um elemento, suas informações são exibidas em uma área de detalhes.

## Funcionalidades

| Funcionalidade                | Descrição                                                             |
| ----------------------------- | --------------------------------------------------------------------- |
| **Tabela Periódica**          | Representação visual dos elementos químicos organizados em 18 colunas |
| **Interação com elementos**   | Destaque visual ao passar o mouse sobre cada elemento                 |
| **Informações dos elementos** | Exibição do nome e massa atômica do elemento selecionado              |
| **Classificação visual**      | Elementos diferenciados por cores conforme sua categoria              |
| **Layout com CSS Grid**       | Posicionamento dos elementos utilizando linhas e colunas              |

---

## Tecnologias Utilizadas

* **HTML5** — Estrutura e organização da aplicação
* **CSS3** — Estilização, responsividade e construção da tabela com CSS Grid
* **JavaScript** — Interatividade e manipulação dos elementos

---

## Conceitos Aplicados

* CSS Grid
* Variáveis CSS
* Flexbox
* Eventos de mouse com JavaScript
* Manipulação do DOM
* HTML `data-*` attributes
* Estruturação semântica de páginas
* Organização visual de informações

## A tabela utiliza um grid de 18 colunas e posiciona cada elemento por meio das propriedades `grid-column` e `grid-row`, utilizando variáveis CSS para definir suas posições.

## Estrutura do Projeto

```text
tabela-periodica/
├── index.html    # Página principal e estrutura da tabela
└── README.md     # Documentação do projeto
```

---

## Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/matheuscarvalhotech/tabela-periodica.git
```

2. Acesse a pasta:

```bash
cd tabela-periodica
```

3. Abra o arquivo `index.html` no navegador.

Também é possível utilizar a extensão **Live Server** no VS Code para executar o projeto localmente.

---

## Interação

## Cada elemento possui informações armazenadas em atributos `data-*`, como nome e massa atômica. O JavaScript utiliza eventos de entrada e saída do mouse para atualizar dinamicamente a área de detalhes da interface.

## Contexto Acadêmico

Projeto desenvolvido como atividade acadêmica da **Universidade Anhembi Morumbi**, com foco no desenvolvimento front-end e aplicação prática de HTML, CSS e JavaScript.

---

## Licença

Este projeto foi desenvolvido para fins acadêmicos e educacionais.
