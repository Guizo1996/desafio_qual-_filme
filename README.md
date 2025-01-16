# Jogo "Qual é o Filme?"

O jogo "Qual é o Filme?" é um jogo interativo onde dois jogadores tentam adivinhar o nome de um filme com base em pistas fornecidas pelo primeiro jogador. O segundo jogador tem até 5 tentativas para acertar o nome do filme. A cada erro, uma nova pista é exibida, e o objetivo é acertar o filme antes de esgotar as tentativas.

## Como Jogar

1. O **Jogador 1** escolhe um filme e fornece 5 dicas sobre o filme escolhido.
2. O **Jogador 2** tem 5 tentativas para adivinhar o nome do filme com base nas dicas fornecidas.
3. A cada tentativa errada, uma nova pista é exibida.
4. O jogo continua até o **Jogador 2** adivinhar corretamente o filme ou até que as tentativas se esgotem.
5. O **Jogador 2** ganha pontos dependendo de quantas dicas ele usou para acertar o filme.

## Instruções

### Regras do Jogo:
- O **Jogador 1** deve fornecer 5 dicas sobre o filme.
- O **Jogador 2** tem 5 chances para tentar adivinhar o filme.
- Cada rodada revela uma pista adicional a cada erro.
- O número de dicas usadas para adivinhar o filme afeta a pontuação final:
    - **1 dica**: +100 pontos
    - **2 dicas**: +60 pontos
    - **3 dicas**: +40 pontos
    - **4 dicas**: +20 pontos
    - **5 dicas**: +10 pontos

### Como Iniciar:
1. **Jogador 1** escolhe um filme e fornece as dicas.
2. **Jogador 2** tenta adivinhar o nome do filme.
3. O jogo informa se a resposta está correta ou não após cada tentativa.
4. O jogo termina quando o **Jogador 2** acerta o filme ou esgota todas as tentativas.

### Como Funciona:
- O jogo exibe um cabeçalho com instruções no console.
- O **Jogador 1** escolhe o filme e insere as 5 dicas.
- O **Jogador 2** tenta adivinhar o filme após cada dica, até 5 tentativas.
- A pontuação é calculada dependendo de quantas tentativas o **Jogador 2** utilizou.

## Tecnologias Usadas

- **JavaScript**: A linguagem de programação principal utilizada para criar o jogo.
- **Console do Navegador**: O jogo roda diretamente no console do navegador, utilizando prompts e alerts.

## Como Rodar

1. Abra o arquivo HTML em seu navegador.
2. Pressione `CTRL + SHIFT + I` para abrir as Ferramentas de Desenvolvedor.
3. Navegue até o console para interagir com o jogo.
4. O jogo será iniciado automaticamente após o carregamento da página.

## Exemplo de Execução

1. O **Jogador 1** escolhe um filme e fornece 5 dicas.
2. O **Jogador 2** tenta adivinhar o filme.
3. Se o **Jogador 2** errar, mais uma dica será fornecida.
4. Se o **Jogador 2** acertar, o jogo exibe uma mensagem de vitória com a pontuação.
5. Se o **Jogador 2** esgotar as tentativas, o jogo informa a derrota e o nome do filme.

## Como Contribuir

Sinta-se à vontade para contribuir com melhorias, novas funcionalidades ou correções de bugs. Para isso, faça um fork deste repositório, crie uma branch para a sua modificação e envie um pull request.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
