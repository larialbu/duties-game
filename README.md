# Duties-Game

## Descrição

Duties-Game é um jogo de plataforma 2D com tema ambiental, dividido em duas fases. O jogador controla um personagem que deve primeiro coletar lixo reciclável e, em seguida, lutar contra a poluição em uma batalha climática. O objetivo do jogo é conscientizar sobre a importância da reciclagem e os impactos do descarte incorreto do lixo.

## Como Executar

Este é um jogo simples contido em arquivos HTML. Para jogar, siga os passos:

1.  Abra o arquivo `index.html` em qualquer navegador web moderno.
2.  Após completar a primeira fase, você será redirecionado para a segunda fase, `nuvem.html`.

Não é necessário um servidor web para jogar.

## Fases do Jogo

### Fase 1: Coleta de Lixo (`index.html`)

Nesta fase, o jogador deve coletar diferentes tipos de lixo e depositá-los nas lixeiras de reciclagem corretas.

-   **Movimentação:** Teclas `A` e `D` para mover para a esquerda e para a direita.
-   **Pulo:** Tecla `W` para pular.
-   **Interação:** Tecla `E` para coletar lixo do chão ou depositá-lo em uma lixeira.
-   **Batalha de Chefe:** Se o jogador cometer 3 erros, uma batalha contra a "Mega-Lixeira Caótica" é iniciada. Nesta batalha, a tecla `F` é usada para atirar lixo no chefe.

### Fase 2: Batalha Climática (`nuvem.html`)

Após completar a fase de coleta, o jogador avança para a fase do clima. O objetivo é derrotar uma nuvem de poluição.

-   **Movimentação:** O jogador pode se mover e pular para desviar dos raios lançados pela nuvem.
-   **Ataque:** O jogador deve coletar os símbolos de reciclagem (♻️) que caem do céu para causar dano à nuvem.
-   **Aviso:** Esta fase contém efeitos de luzes piscantes que podem ser desconfortáveis para pessoas com epilepsia fotossensível.

## Personagens

-   **Augustinho:** O protagonista do jogo, controlado pelo jogador.
-   **Garii:** Um guia ambiental que fornece instruções na primeira fase.
-   **Mega-Lixeira Caótica:** O chefe da primeira fase, uma lixeira gigante e furiosa.
-   **Reporter:** Uma repórter que guia o jogador na segunda fase.

## Estrutura do Projeto

O jogo está dividido em dois arquivos HTML principais:

-   **`index.html`**: Contém a lógica e os assets da primeira fase (Coleta de Lixo).
-   **`nuvem.html`**: Contém a lógica e os assets da segunda fase (Batalha Climática).

Todo o código (HTML, CSS e JavaScript) está contido dentro desses arquivos. As imagens e GIFs estão na pasta `imagem/`.

## Futuras Melhorias

-   Adicionar mais níveis ou fases.
-   Introduzir novos tipos de inimigos.
-   Melhorar a inteligência artificial dos chefes.
-   Adicionar sons e música de fundo.
-   Criar um sistema de pontuação mais elaborado.