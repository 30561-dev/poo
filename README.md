Exercício POO - Banda Escolar

Nome: Edson Fernando Piacente Barbarini

Descrição

Sistema desenvolvido em Java para representar os instrumentos de uma banda escolar, utilizando os conceitos de Programação Orientada a Objetos.

O sistema possui uma classe abstrata InstrumentoMusical e duas classes concretas: Violao e Bateria.

Conceitos utilizados
Classe abstrata
Herança
Polimorfismo
Encapsulamento
Método abstrato
Método concreto
List<InstrumentoMusical>
Instrumentos
Violão: 6 cordas, feito de madeira.
Bateria: 5 tambores, feita de metal.

Todos os instrumentos começam desafinados. O método afinar() altera o estado do instrumento para afinado.

O método tocar() é abstrato porque cada instrumento produz um som diferente.

Estrutura
model/
  InstrumentoMusical.java
  Violao.java
  Bateria.java
app/
  TesteBanda.java
README.md

Resultado esperado

Ao executar o programa, os instrumentos são afinados e tocados. Ao final, deve ser exibido que 2 instrumentos estão afinados.