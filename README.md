# Aluguel de Jogos de Tabuleiro

Este é um projeto de um site para aluguel de jogos de tabuleiro, desenvolvido com HTML, CSS e JavaScript. O site permite ao usuário visualizar os jogos disponíveis, suas respectivas imagens e alugar ou devolver os jogos de acordo com sua disponibilidade.

## Funcionalidades

- **Exibição de Jogos**: O site exibe uma lista de jogos de tabuleiro com suas imagens e títulos.
- **Aluguel de Jogos**: O usuário pode alugar um jogo clicando no botão "Alugar" abaixo do título do jogo, caso ele esteja disponível.
- **Devolução de Jogos**: Se o jogo já estiver alugado, o usuário pode clicar no botão "Devolver" para devolvê-lo e torná-lo disponível para outros usuários.
  
## Estrutura do Projeto

```bash
aluguel-jogos/
│
├── css/
│   ├── _reset.css        # Estilos de reset (normalização)
│   └── main.css          # Estilos principais do site
│
├── img/
│   ├── fade_bar.svg       # Imagem decorativa
│   ├── hachuras.svg       # Imagem decorativa
│   ├── logo.svg           # Logo do site
│   ├── monopoly.png       # Imagem do jogo "Monopoly"
│   ├── takenoko.png       # Imagem do jogo "Takenoko"
│   └── ticket_to_ride.png # Imagem do jogo "Ticket to Ride"
│
├── js/
│   └── app.js            # Lógica de aluguel e devolução dos jogos
│
├── index.html            # Arquivo principal do site
└── README.md             # Documentação do projeto
```

## Como usar

1. Clone este repositório:
    ```bash
    git clone https://github.com/glelisv/aluguel-jogos.git
    ```
2. Abra o arquivo `index.html` em um navegador para iniciar o site.

## Tecnologias Utilizadas

- **HTML5**: Estrutura e marcação do conteúdo.
- **CSS3**: Estilização do layout e design visual.
- **JavaScript**: Lógica de aluguel e devolução dos jogos.

## Detalhes do Projeto

### Página Principal (`index.html`)

A página exibe a lista de jogos com as seguintes funcionalidades:

- **Imagem e Título do Jogo**: Cada jogo tem sua imagem e título visíveis ao usuário.
- **Botão de Ação**: Abaixo de cada jogo há um botão que alterna entre "Alugar" e "Devolver", de acordo com o estado atual do jogo.
  
### Estilos (`_reset.css` e `main.css`)

- O arquivo `_reset.css` contém os estilos para normalizar a exibição dos elementos entre diferentes navegadores.
- O arquivo `main.css` contém os estilos principais do layout e componentes visuais do site.

### Lógica (`app.js`)

O arquivo `app.js` contém a lógica que controla a interação dos usuários com os jogos, incluindo:
- Alternância entre "Alugar" e "Devolver" com base no estado de disponibilidade do jogo.
- Alteração do status do jogo no botão conforme o usuário aluga ou devolve o jogo.

## Personalizações

- **Imagens de Jogos**: Para adicionar mais jogos, basta incluir novas imagens na pasta `img/` e adicionar o código correspondente no arquivo `index.html`.
- **Estilos**: Modifique o arquivo `main.css` para ajustar o design e layout de acordo com suas preferências.