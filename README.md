# 🛒 Compra Maluca – Tratamento de Exceções em Java

## 🎯 Objetivo
Esta atividade tem como foco o **levantamento e tratamento de exceções personalizadas** em Java, simulando um sistema de carrinho de compras.

Você deverá implementar o código para tratar as seguintes situações por meio de exceções:

- `ItemAlreadyExists`: lançada quando há tentativa de adicionar um item com o mesmo nome de outro já presente no carrinho;
- `NotEnoughSpace`: lançada quando não há mais espaço para adicionar novos itens (limite de 10 itens diferentes no carrinho);
- `NotFound`: lançada ao tentar remover ou buscar um item que **não existe** no carrinho;
- `NullParameters`: lançada quando algum método recebe **um parâmetro nulo**.

---

## 🧭 Instruções
- As classes `Cart.java` e `Buy.java` **estão incompletas** e precisam ser modificadas para implementar corretamente o tratamento e levantamento das exceções descritas.
- A classe `Main.java` **já está pronta e não deve ser modificada**. Ela serve apenas para **testar** o comportamento do sistema e verificar se as exceções estão sendo levantadas corretamente.
- Todas as exceções mencionadas já estão declaradas como classes. Você **deve utilizá-las** conforme a lógica do programa.

---

## 🧩 Descrição das Classes

- `Main`  
  Classe principal que executa operações de adicionar, buscar e remover itens. Já implementada. **Não altere.**

- `Buy`  
  Classe responsável pelos métodos de compra, como adicionar, remover e buscar itens no carrinho. Deve conter o **tratamento de exceções**.

- `Cart`  
  Classe que gerencia o estado do carrinho e a lógica de manipulação dos itens (adicionar, remover, buscar). Deve conter o **levantamento das exceções**.

- `Items`  
  Representa um item da loja, com os atributos `nome`, `preço` e `quantidade`.

- `ItemAlreadyExists`  
  Exceção personalizada para quando um item com o mesmo nome já está no carrinho.

- `NotEnoughSpace`  
  Exceção personalizada para quando o carrinho atinge seu limite de 10 itens diferentes.

- `NotFound`  
  Exceção personalizada para quando um item não é encontrado (ao buscar ou remover).

- `NullParameters`  
  Exceção personalizada para quando é passado um parâmetro nulo a um método.
