# Sistema de Personagens de Jogo de RPG

## Descrição

Neste exercício, você vai criar um sistema para gerenciar diferentes tipos de personagens em um jogo de RPG utilizando herança em Java. O objetivo é entender como a herança pode ser usada para criar uma hierarquia de classes e compartilhar atributos e métodos comuns, além de implementar funcionalidades específicas para cada tipo de personagem.

Você vai implementar um sistema que gerencia diferentes tipos de personagens em um jogo de RPG. Haverá três classes: `Guerreiro`, `Mago` e `Arqueiro`. Cada tipo de personagem terá atributos e métodos específicos.

## Classes a serem implementadas

### Personagem
- **Atributos:**
  - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel` e `pontosDeVida`
  - Getters e setters para os atributos
  - Método abstrato `atacar()`
  - Método abstrato `defender()`

### Guerreiro (subclasse de Personagem)
- **Atributos:**
- - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
  - `forca` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel`, `pontosDeVida` e `forca`
  - Getters e setters para o atributo `forca`
  - Implementa o método `atacar()` para realizar um ataque físico (Ex.: "Boromir ataca com força 100")
  - Implementa o método `defender()` para aumentar a defesa temporariamente (Ex.: "Boromir aumenta sua defesa temporariamente!")

### Mago (subclasse de Personagem)
- **Atributos:**
- - `nome` (String)
  - `nivel` (int)
  - `pontosDeVida` (int)
  - `mana` (int)
- **Métodos:**
  - Construtor que inicializa `nome`, `nivel`, `pontosDeVida` e `mana`
  - Getters e setters para o atributo `mana`
  - Implementa o método `atacar()` para lançar um feitiço (Ex.: "Gandalf lança um feitiço com 25 de mana")
  - Implementa o método `defender()` para criar uma barreira mágica (Ex.: "Gandalf cria uma barreira mágica!")

### Arqueiro (subclasse de Personagem)
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
