# Duties-Game

## Descrição

Duties-Game é um jogo de plataforma 2D com tema ambiental. O jogador controla um personagem que deve coletar diferentes tipos de lixo e depositá-los nas lixeiras de reciclagem corretas. O jogo possui uma fase principal de coleta e uma batalha de chefe que é acionada se o jogador cometer muitos erros.

## Como Jogar

Este é um jogo simples contido em um único arquivo HTML (`index.html`). Para jogar, basta abrir este arquivo em qualquer navegador web moderno. Não é necessário um servidor web.

## Funcionalidades do Jogo

### Jogador

- **Movimentação:** Teclas `A` e `D` para mover para a esquerda e para a direita.
- **Pulo:** Tecla `W` para pular.
- **Interação:** Tecla `E` para coletar lixo do chão ou depositá-lo em uma lixeira.
- **Ataque (Batalha contra o Chefe):** Tecla `F` para atirar o lixo que está segurando.
- **Vida:** O jogador possui uma barra de vida que é exibida durante a batalha contra o chefe.

### Lixo

- **Tipos:** Existem 5 tipos de lixo no jogo: papel, plástico, vidro, metal e orgânico.
- **Coleta:** O lixo pode ser coletado pelo jogador ao se aproximar e pressionar a tecla `E`.
- **Munição:** Durante a batalha contra o chefe, novos itens de lixo aparecem periodicamente no cenário e servem como munição.

### Lixeiras

- Cada tipo de lixo possui uma lixeira correspondente com uma cor específica.
- O jogador deve depositar o lixo na lixeira correta para pontuar.
- Depositar o lixo na lixeira errada conta como um erro.

### NPC (Personagem Não-Jogável)

- Há um guia ambiental no início do jogo que fornece as instruções.
- O NPC é um personagem humano que fica parado em uma parte do cenário.

### Chefe

- **Ativação:** A batalha contra o chefe ("Mega-Lixeira Caótica") começa se o jogador cometer 3 erros na fase de reciclagem.
- **Ataques:** O chefe atira projéteis de lixo em direção ao jogador.
- **Derrota:** O jogador pode derrotar o chefe atirando lixo nele. O chefe possui uma barra de vida que é reduzida a cada acerto.

## Estrutura do Código

O jogo inteiro está contido no arquivo `index.html`.

- **CSS:** O estilo do jogo, incluindo a aparência dos personagens, cenário e interface, está dentro da tag `<style>`.
- **JavaScript:** Toda a lógica do jogo está dentro da tag `<script>`.

### Classes Principais em JavaScript

- `Player`: Controla o personagem do jogador, incluindo movimento, pulo, vida e ações de pegar/soltar/atirar.
- `Trash`: Representa os itens de lixo que podem ser coletados.
- `Bin`: Representa as lixeiras de reciclagem.
- `NPC`: Representa o guia ambiental.
- `Boss`: Controla o comportamento e a aparência do chefe.
- `Projectile`: Representa os projéteis de lixo atirados pelo jogador e pelo chefe.

## Futuras Melhorias

- Adicionar mais níveis ou fases.
- Introduzir novos tipos de inimigos.
- Melhorar a inteligência artificial do chefe.
- Adicionar sons e música de fundo.
- Criar um sistema de pontuação mais elaborado.
