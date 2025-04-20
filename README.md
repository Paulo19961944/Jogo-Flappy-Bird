# Super Flappy Bird
Super Flappy Bird é um jogo web inspirado no clássico Flappy Bird, com recursos adicionais como níveis, moedas, nuvens animadas e uma interface estilizada. Desenvolvido com HTML5 Canvas, CSS e JavaScript, o jogo oferece uma experiência divertida e desafiadora para jogadores de todas as idades.
Funcionalidades

**Jogabilidade Clássica:** Controle o pássaro para evitar canos e coletar moedas.<br></br>
**Sistema de Níveis:** Progrida através de níveis com dificuldade crescente, desbloqueando recompensas.<br></br>
**Moedas e Recompensas:** Colete moedas durante o jogo e receba bônus ao subir de nível.<br></br>
**Interface Animada:** Inclui nuvens em movimento, animação do pássaro e efeitos visuais.<br></br>
**Controles:** Suporta clique do mouse, toque na tela (para dispositivos móveis) e teclas (espaço ou seta para cima).<br></br>
**Telas Interativas:** Tela inicial, tela de game over e tela de progressão de nível.<br></br>
**API Externa:** Integração com uma API para manipulação de moedas, níveis e pontuação.

## Como Executar

Pré-requisitos: Um navegador web moderno (Chrome, Firefox, Safari, etc.).

### Instruções:
- Faça o download ou clone este repositório.
- Abra o arquivo index.html em um navegador web.
- Clique em "INICIAR" para começar o jogo.


### Controles:
**Mouse/Toque:** Clique ou toque na tela para fazer o pássaro voar.
**Teclado:** Pressione a tecla Espaço ou Seta para Cima para voar.



## Estrutura do Projeto

**index.html:** Contém a estrutura HTML, estilos CSS e o código JavaScript do jogo.
**Estilos CSS:** Interface estilizada com gradiente de fundo, botões animados e sombras.

- Animações como o efeito de pulsar no título e barra de progresso de nível.


**JavaScript:**
- Lógica do jogo implementada com HTML5 Canvas.
- Gerenciamento de estados (início, jogo, game over, nível concluído).
- Sistema de colisão para canos e moedas.
- Animações para o pássaro, moedas, nuvens e chão.
- API window.flappyGame para integração externa.



## API Externa
O jogo expõe uma API para integração com sistemas externos (como PIX). As funções disponíveis são:

**flappyGame.addCoins(amount):** Adiciona uma quantidade de moedas e retorna o total atual.
**flappyGame.getCoins():** Retorna o número total de moedas.
**flappyGame.getLevel():** Retorna o nível atual.
**flappyGame.getScore():** Retorna a pontuação atual.

## Exemplo de uso:

```javascript
window.flappyGame.addCoins(10); // Adiciona 10 moedas
console.log(window.flappyGame.getLevel()); // Exibe o nível atual
```

### Personalização
Você pode personalizar o jogo ajustando as seguintes variáveis no código JavaScript:

**gravity:** Controla a força da gravidade no pássaro.
**gameSpeed:** Define a velocidade do jogo (movimento de canos, moedas, etc.).
**pipeGap:** Ajusta o espaço entre os canos.
**pipeSpawnInterval:** Intervalo de tempo para criação de novos canos.
**pointsToNextLevel:** Pontos necessários para subir de nível.

## Contribuições
Contribuições são bem-vindas! Para sugerir melhorias ou corrigir bugs:

### Faça um fork do repositório.
- Crie uma branch para sua feature (git checkout -b feature/nova-funcionalidade).
- Commit suas alterações (git commit -m 'Adiciona nova funcionalidade').
- Envie para o repositório remoto (git push origin feature/nova-funcionalidade).
- Abra um Pull Request.

## Link do Projeto
[Clique aqui para acessar o Jogo](https://paulo19961944.github.io/Jogo-Flappy-Bird/)

## Licença
Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
