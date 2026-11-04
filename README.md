# Calculadora de média acadêmica

Exercício de seleção de elementos do DOM com JavaScript (formulário com nome e duas notas).

## Como rodar
Abra a pasta no VS Code e use a extensão **Live Server** em `form.html` (botão "Go Live"), depois abra o Console do navegador (F12) para ver os `console.log`.

## Arquivos
- `form.html`: formulário (nome, nota 1, nota 2, botões)
- `form.js`: seleciona o formulário e os campos com `querySelector`
- `page.html`: exemplos de `getElementById`, `getElementsByClassName`, `querySelector` e `addEventListener`
<div align="center">

# 📺 Vendas de TVs e Acessórios

**Vitrine online de TVs e acessórios, feita com HTML, CSS e JavaScript puros.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Univille](https://img.shields.io/badge/Univille-Joinville-198754?style=for-the-badge)

*Projeto acadêmico desenvolvido na **Univille, em Joinville (SC)**.*

</div>

---

## 📖 Sobre o projeto

Uma loja fictícia que reúne TVs e acessórios em páginas navegáveis. O projeto foi construído ao longo dos exercícios da faculdade para praticar HTML semântico, CSS moderno (Flexbox, Grid, transições e animações) e um pouco de JavaScript para deixar a página interativa.

> ⚠️ **Demonstração:** preços, produtos e formulários são apenas ilustrativos. Cadastro, login e feedback validam os campos no navegador, mas **nenhum dado é enviado ou armazenado**.

## ✨ Funcionalidades

- **Página inicial** com banner, destaque de promoção e menu fixo no topo.
- **Categoria de TVs** com produtos em cartões (CSS Grid) e também em tabela.
- **Categoria de acessórios** com soundbars e links para a página do fabricante.
- **Busca em tempo real:** filtra os produtos por marca, preço ou parcelamento enquanto você digita.
- **Cadastro e login** em abas, com validação de campos (modo demonstração).
- **Formulário de feedback** com tipo de assunto, mensagem e nota de 1 a 5.
- **Layout responsivo:** 3 colunas no desktop, 2 no tablet e 1 no celular, com a tabela rolável na horizontal.
- **Animações e transições** nos títulos, links e imagens, com suporte à opção "reduzir movimento" do sistema.
- **Estilo de impressão** que esconde o menu e o rodapé.

## 🗂️ Páginas

| Arquivo | O que é |
| --- | --- |
| `products.html` | Página inicial da loja |
| `category_tvs.html` | Catálogo de TVs, busca, cadastro/login e feedback |
| `category_acessories.html` | Catálogo de acessórios (soundbars) |
| `styles.css` | Estilos compartilhados por todas as páginas |

## 🛠️ Tecnologias

| Camada | O que foi usado |
| --- | --- |
| Estrutura | HTML5 semântico (`header`, `nav`, `main`, `section`, `article`, `footer`) |
| Estilo | CSS3: variáveis de cor, Flexbox, Grid, media queries, `@keyframes` |
| Interação | JavaScript puro, sem bibliotecas |
| Fonte | Arial / Helvetica |

Sem frameworks, sem build e sem instalação de pacotes.

## 🚀 Como rodar

Você só precisa de um navegador moderno (Chrome, Edge, Firefox ou Safari) e de **conexão com a internet**, porque as imagens dos produtos são carregadas de sites externos.

### Opção 1: baixar e abrir (mais simples)

1. Na página do repositório, clique em **Code → Download ZIP**.
2. Extraia o arquivo `.zip`.
3. Dê dois cliques em **`products.html`** para abrir no navegador.

### Opção 2: clonar com Git

```bash
git clone https://github.com/igoroouriques/dew.git
cd dew
```

Depois abra o `products.html` no navegador.

### Opção 3: VS Code com Live Server

1. Abra a pasta do projeto no VS Code.
2. Instale a extensão **Live Server**.
3. Clique com o botão direito em `products.html` e escolha **Open with Live Server**.

### Opção 4: servidor local com Python

```bash
cd dew
python -m http.server 8000
```

Acesse `http://localhost:8000/products.html`.

## 📁 Estrutura

```
dew/
├── products.html              # página inicial
├── category_tvs.html          # TVs + busca, conta e feedback
├── category_acessories.html   # acessórios
└── styles.css                 # estilos globais e responsivos
```

## 📱 Responsividade

| Largura da tela | Layout |
| --- | --- |
| Acima de 1024 px | Cartões em 3 colunas |
| Até 1024 px | Cartões em 2 colunas |
| Até 768 px | 1 coluna, parcelamento oculto nos cartões, tabela com rolagem |
| Até 480 px | Fontes e botões reduzidos |

## 🎯 O que foi praticado

- Seletores e especificidade em CSS
- Layout com **Flexbox** e **Grid** (áreas nomeadas)
- Media queries e design responsivo
- Transições, `transform` e animações com `@keyframes`
- Acessibilidade básica: `alt` nas imagens, rótulos nos formulários, `aria-live` nas mensagens e `prefers-reduced-motion`
- Manipulação do DOM com JavaScript (busca, abas e formulários)

## 👤 Autor

**Igor de Oliveira Ouriques**
Estudante de Engenharia de Software · Univille, Joinville (SC)

## 👤 Professora

**Sabrina Boing Moreira**
Professora das matérias de Dew e Apc_i - Univille, Joinville (SC)

[![GitHub](https://img.shields.io/badge/GitHub-igoroouriques-181717?style=flat-square&logo=github)](https://github.com/igoroouriques)
[![Instagram](https://img.shields.io/badge/Instagram-igoroouriques-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/igoroouriques)

---

<div align="center">

Projeto acadêmico, sem fins comerciais. As marcas citadas pertencem aos seus respectivos donos.

</div>
