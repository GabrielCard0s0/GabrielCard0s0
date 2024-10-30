# Olá, eu sou o Gabriel Cardoso! 👋

### 👨‍💻 Sobre mim
Sou um desenvolvedor Python com interesse em expandir meus conhecimentos em JavaScript, HTML e CSS. Estou sempre em busca de aprender e me aprimorar na área de programação, especialmente com Python.

### 💻 Competências
- **Linguagens de programação**: Python, JavaScript, HTML, CSS

### 📂 Projetos
Confira meus repositórios no GitHub para ver alguns dos projetos em que estou trabalhando. Sinta-se à vontade para explorar e dar feedback!

### 🎮 Interesses
Fora da programação, gosto muito de:
- Jogar
- Assistir séries e filmes
- Apreciar animes

### 🎨 Estilo
Gosto de designs complexos, mas minimalistas, que não utilizam muitas cores.

### 📫 Vamos nos conectar?
Sinta-se à vontade para entrar em contato ou contribuir com meus projetos. Estou aberto a colaborações e dicas!
Meu contato pode ser visto no perfil.

### ✉ P.S:
Estou viciado em pedir para o ChatGPT comentar meus códigos. Preguiça? Comodidade? Prática? Talvez tudo isso? Tire suas próprias conclusões.

Obrigado por visitar meu perfil! 😊

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
