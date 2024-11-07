
# BoardToim

**BoardToim** é um jogo de tabuleiro multiplayer baseado em navegador que oferece uma experiência de combate estratégico com diferentes tipos de peças e regras de eliminação. Desenvolvido com tecnologias modernas, como Bootstrap, jQuery e PeerJS, **BoardToim** permite que dois jogadores conectem-se remotamente para batalhas intensas em um tabuleiro dinâmico.

## 🚀 Link para Jogar

👉 [Clique aqui para jogar!](https://tonicjunior.github.io/BoardToim/)


## 📂 Links do Projeto

   <a href="https://github.com/tonicjunior/BoardToim" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?logo=github" alt="GitHub">
</a>
<a href="https://nubank.com.br/cobrar/3upen/672bafe3-8951-4aae-8e53-d86628e67a1a" target="_blank">
    <img src="https://img.shields.io/badge/Investir%20no%20projeto-Informa%C3%A7%C3%B5es-4CAF50" alt="Investir">
</a>

## Índice

- [Funcionalidades](#funcionalidades)
- [Configuração e Execução](#configuração-e-execução)
- [Regras do Jogo](#regras-do-jogo)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Usadas](#tecnologias-usadas)
- [Licença](#licença)

## Funcionalidades

- **Multiplayer Peer-to-Peer**: Conexão entre dois jogadores usando IDs de sessão gerados via PeerJS.
- **Interface Responsiva**: Layout adaptável para dispositivos móveis e desktops, utilizando Bootstrap.
- **Regras Customizáveis**: Cada peça possui um conjunto específico de regras para movimentação e ataque.
- **Timer de Turno**: Limite de 15 segundos para cada jogador realizar uma ação, destacando a vez ativa.
- **Modal Interativo**: Modal de confirmação e exibição de informações de jogo.
- **Cores Dinâmicas das Peças**: Peças coloridas com atributos específicos que são sorteados a cada nova partida.

## Configuração e Execução

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/tonicjunior/BoardToim.git
   cd BoardToim
   ```

2. **Instale as Dependências**: O projeto utiliza CDNs para as bibliotecas externas, portanto, não há dependências adicionais.

3. **Execute o Jogo**:
   Abra o arquivo `index.html` em seu navegador ou utilize uma extensão de servidor local no VSCode para visualizar o jogo.

## 🏰 Regras do Jogo

Cada jogador comanda um exército de peças lendárias, cada uma com habilidades especiais e destemidas. Prepare-se para uma batalha épica:

- <img src="src/assets/images/c.png" width="44" alt="Guerreiro"> **Guerreiro (O Aniquilador de Dragões) - 3 peças**  
  Esses heróis de músculos e espadas enfrentam dragões sem piscar e não hesitam em derrubar outros guerreiros em batalha. Mas, se ousarem atacar uma Bruxa ou um Mago, suas armaduras se desfazem, e eles viram poeira. E isso não é tudo – ao atacar a própria Morte, ela os ceifa e leva suas almas consigo. Sua defesa pode não ser das melhores, mas ninguém pode negar a coragem do estilo “vou, mas caio lutando”, algo digno de admiração.

- <img src="src/assets/images/w.png" width="44" alt="bruxa"> **Bruxa (A Reveladora de Segredos) - 2 peças**  
  As Bruxas são o verdadeiro pesadelo para peças furtivas! Quando atacam, só conseguem derrotar guerreiros. Mas isso é apenas o começo: se duas Bruxas se enfrentam, o encontro se transforma em um espetáculo sobrenatural – ambas desaparecem numa explosão mágica digna de fogos de artifício. Além disso, todos os adversários escondidos, como a Morte e o Dragão, são revelados, mostrando suas verdadeiras formas, o que pode ser devastador! Apesar de poderosas, não são invencíveis (quem é, afinal?), então, se um Mago, a Morte, um Dragão ou outra Bruxa resolve atacá-las, é o fim da linha.

- <img src="src/assets/images/m.png" width="44" alt="mago"> **Mago (O Autêntico Feiticeiro do Campo) - 2 peças**  
  Magos são os estrategistas do campo de batalha, mandando Guerreiros e Bruxas pelos ares sem esforço. Mas, quando dois Magos se enfrentam, a disputa vira um duelo épico onde o primeiro a conjurar magia leva a vitória! Só que há um problema: se um Dragão entra na brincadeira, o Mago vira churrasco rapidinho, eles são imunes as suas magias (olha que ousadia). E embora não sejam exatamente frágeis, não é como se eles fossem feitos de armadura de ferro! Qualquer outro Mago ou um Dragão que decida encará-los de frente... bom, é tchau para nossos ilustres conjuradores.

- <img src="src/assets/images/f.png" width="44" alt="morte"> **Morte (O Cortejo Silencioso) - 2 peças**  
  Mortes não brincam. Elas são metódicas e letais (como o nome bem indica). Bruxas? Eliminadas. Guerreiros? Magos? Também. Mas, contra um Dragão... bom, às vezes até a Morte sabe que é melhor esperar. Ao ceifar qualquer peça que não seja uma Bruxa, elas se despedem do campo de batalha com suas almas ceifadas. Porém, se uma Bruxa ousar atacar, a Morte apenas se revela e permanece em batalha, lançando um sorriso sinistro – como se dissesse: “Vai encarar?”

- <img src="src/assets/images/d.png" width="44" alt="dragao"> **Dragão (O Terror Alado) - 1 peça**  
  O Dragão é o que mais se aproxima de uma força imparável neste jogo! Ele destroça Guerreiros, frita Magos, desintegra Bruxas e até faz a Morte pensar duas vezes. Mas cuidado: se topar com outro Dragão, teremos um espetáculo de fogo e fúria, onde ambos se reduzem a cinzas em um épico empate destrutivo. Imune a magias e praticamente invulnerável, o Dragão tem apenas um verdadeiro ponto fraco: Guerreiros audaciosos que, com astúcia, conseguem surpreendê-lo. Mas fora isso, ele reina absoluto!

---

⚔️ **Aviso de Guerra**: Quando a batalha termina e um jogador conquista a vitória, o jogo recomeça, mas o caos do destino redistribui todas as peças. Cada nova batalha reserva surpresas!

## Estrutura do Projeto

- **index.html**: Interface principal do jogo.
- **styles.css**: Estilos CSS personalizados.
- **app.js**: Lógica do jogo e controle de fluxo.

```plaintext
BoardToim/
├── index.html              # Estrutura principal da aplicação
├── src/
│    └──  assets
│        └──  images        # Pasta com as imagens do jogo
│   ├── app.js              # Lógica do jogo e manipulação de eventos
├── styles/
│   └── style.css           # Estilos customizados para o jogo
└── README.md               # Documentação do projeto
```

## Tecnologias Usadas

- **HTML5 & CSS3**: Estrutura e estilização da interface do jogo.
- **Bootstrap 5**: Para o design responsivo e componentes UI.
- **jQuery 3.6.0**: Manipulação DOM simplificada.
- **PeerJS 1.5.0**: Implementação de comunicação peer-to-peer para conectar jogadores.
- **JavaScript ES6+**: Lógica de jogo e manipulação de eventos.

## Licença

Este projeto está licenciado sob a licença MIT. Sinta-se à vontade para modificá-lo e compartilhá-lo.

---

👾 Divirta-se jogando **BoardToim** e prepare-se para uma batalha épica!
