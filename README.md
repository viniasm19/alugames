# 🎲 AluGames

Plataforma web para aluguel de boardgames, desenvolvida como projeto de estudo de HTML, CSS e JavaScript.

## 📋 Sobre o projeto

O AluGames permite visualizar um catálogo de jogos de tabuleiro e controlar quais estão alugados ou disponíveis. Ao clicar em **Alugar**, o jogo é marcado como indisponível e o botão muda para **Devolver**. O total de jogos alugados é exibido no console do navegador.

## 🖥️ Demonstração

![Preview do projeto](img/logo.svg)

O projeto conta com três jogos no catálogo:
- Monopoly
- Ticket to Ride
- Takenoko

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

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura das páginas
- **CSS3** — estilização e layout responsivo
- **JavaScript** — lógica de aluguel e manipulação do DOM

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

## ⚙️ Funcionalidades

- [x] Exibir catálogo de jogos
- [x] Alugar um jogo (muda visual e botão)
- [x] Devolver um jogo com confirmação
- [x] Contador de jogos alugados no console

## 📚 Aprendizados

Projeto desenvolvido durante o curso da **Alura**, explorando:
- Manipulação do DOM com JavaScript
- Uso de `classList` para alternar estilos
- Eventos de clique e `confirm()` do navegador
- Organização de projeto front-end

## 👤 Autor

Feito por **Vini Melo**  
[GitHub](https://github.com/viniasm19)
