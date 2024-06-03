# Sistema de Personagens de Jogo de RPG

## Descrição

Neste exercício, você vai criar um sistema para gerenciar diferentes tipos de personagens em um jogo de RPG utilizando herança em Java. O objetivo é entender como a herança pode ser usada para criar uma hierarquia de classes e compartilhar atributos e métodos comuns, além de implementar funcionalidades específicas para cada tipo de personagem.

Você vai implementar um sistema que gerencia diferentes tipos de personagens em um jogo de RPG. Haverá 5 classes: `Guerreiro`, `Bárbaro`, `Mago`, `Feiticeiro` e `Arqueiro`. Cada tipo de personagem terá atributos e métodos específicos.

## Classes a serem implementadas

### Guerreiro
- **Atributos:**
- - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
  - `forca` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel`, `pontosDeVida` e `forca`
  - Getters e setters para o atributo `forca`
  - Implementa o método `atacar()` para realizar um ataque físico (Ex.: "Boromir ataca com força 100")
  - Implementa o método `defender()` para usar um escudo para defesa (Ex.: "Boromir usa o escudo para defesa!")

 ### Bárbaro
- **Atributos:**
- - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
  - `furia` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel`, `pontosDeVida` e `furia`
  - Getters e setters para o atributo `furia`
  - Implementa o método `atacar()` para realizar um ataque físico (Ex.: "Gorbag ataca com força 100")
  - Implementa o método `defender()` para aumentar a defesa temporariamente (Ex.: "Gorbag aumenta sua defesa temporariamente!")

### Mago
- **Atributos:**
- - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
  - `mana` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel`, `pontosDeVida` e `mana`
  - Getters e setters para o atributo `mana`
  - Implementa o método `atacar()` para lançar um feitiço (Ex.: "Gandalf lança uma magia com 25 de mana")
  - Implementa o método `defender()` para criar uma barreira mágica (Ex.: "Gandalf cria uma barreira mágica!")
 
### Feiticeiro
- **Atributos:**
- - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
  - `mana` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel`, `pontosDeVida` e `mana`
  - Getters e setters para o atributo `mana`
  - Implementa o método `atacar()` para lançar um feitiço (Ex.: "Angmar lança um feitiço com 25 de mana")
  - Implementa o método `defender()` para criar uma barreira mágica (Ex.: "Angmar cria uma barreira mágica!")

### Arqueiro
- **Atributos:**
- - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
  - `precisao` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel`, `pontosDeVida` e `precisao`
  - Getters e setters para o atributo `precisao`
  - Implementa o método `atacar()` para realizar um ataque à distância (Ex.: "Legolas realiza um ataque à distância com precisão de 45")
  - Implementa o método `defender()` para esquivar de ataques (Ex.: "Legolas esquiva do ataque!")

## Objetivo

Entender como a herança permite criar subclasses especializadas e compartilhar comportamento comum através da superclasse, facilitando a reutilização de código e a implementação de funcionalidades específicas para cada tipo de personagem.

## Instruções

1. Implemente todas as classes conforme descrito acima.
2. Compile e execute a classe `Main` para testar o sistema.
3. Verifique se os ataques e defesas dos personagens são executados corretamente de acordo com as regras específicas de cada tipo de personagem.

## Novo Requisito: Adicionar Habilidades aos Personagens
O jogo evoluiu, e agora cada personagem pode ter uma habilidade especial. As habilidades disponíveis são:

- Curar a si mesmo: Permite ao personagem recuperar uma parte de seus pontos de vida.
- Curar outro personagem: Permite ao personagem curar um aliado, restaurando uma parte dos pontos de vida dele.
- Teletransporte: Permite ao personagem se mover instantaneamente para um local seguro.
- Invisibilidade: Permite ao personagem ficar invisível por um período de tempo, evitando ataques.

Cada personagem pode possuir apenas uma dessas habilidades. A escolha da habilidade deve ser feita no momento da criação do personagem ou durante o andamento do jogo.
