# 🎲 AluGames

Aplicação web de aluguel de jogos de tabuleiro, desenvolvida como projeto de estudo de HTML, CSS e JavaScript.

## 📋 Sobre o projeto

O AluGames simula um catálogo de boardgames disponíveis para aluguel. Cada jogo listado pode ser alugado ou devolvido com um clique, e o sistema mantém o controle visual (e no console) de quantos jogos estão alugados no momento.

## 🎮 Como usar

1. Veja os jogos disponíveis no catálogo
2. Clique em **Alugar** para marcar um jogo como alugado
3. O jogo alugado fica com a capa escurecida e o botão muda para **Devolver**
4. Clique em **Devolver** para liberar o jogo novamente (com confirmação antes de efetivar)

## ✨ Funcionalidades

- Alternância de status entre "Alugar" e "Devolver" por jogo
- Efeito visual (escurecimento da capa) indicando jogo alugado
- Confirmação antes de devolver um jogo
- Contagem de jogos alugados exibida no console
- Contagem recalculada automaticamente ao carregar a página

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura da página
- **CSS3** — estilização com gradientes, sombras e tipografia customizada (Google Fonts)
- **JavaScript** — lógica de status dos jogos e manipulação do DOM

## 📁 Estrutura de arquivos

```
alugames/
├── index.html
├── css/
│   ├── main.css
│   └── _reset.css
├── js/
│   └── app.js
└── img/
    ├── logo.svg
    ├── fade_bar.svg
    ├── hachuras.svg
    ├── monopoly.png
    ├── takenoko.png
    └── ticket_to_ride.png
```

## 🚀 Como executar

1. Clone o repositório:

```bash
git clone https://github.com/viniasm19/alugames.git
```

2. Abra a pasta do projeto:

```bash
cd alugames
```

3. Abra o arquivo `index.html` no seu navegador — não é necessário nenhum servidor ou instalação.

## 📚 Aprendizados

Projeto desenvolvido como estudo de JavaScript, explorando:

- Manipulação de classes CSS via JavaScript (`classList.add`/`remove`/`contains`)
- Seleção de elementos filhos com `querySelector`
- Uso de `confirm()` para ações destrutivas
- Contagem de elementos com `querySelectorAll`
- Evento `DOMContentLoaded` para inicializar estado ao carregar a página

## 👤 Autor

Feito por **Vini Melo** — [GitHub](https://github.com/viniasm19)
