
# Desafio Sudoku DIO

\<p align="center"\>
\<img src="dio.png" alt="Logo DIO"\>
\</p\>

Este projeto é uma **implementação em console do clássico jogo Sudoku**, desenvolvido como parte do **Desafio da Digital Innovation One (DIO)**. Ele oferece uma interface interativa para que o usuário possa jogar, inserir números, verificar o status do tabuleiro e resolver o quebra-cabeça.

---

## 🚀 Funcionalidades

O jogo Sudoku oferece as seguintes opções para uma experiência completa no terminal:

* **Iniciar Novo Jogo**: Comece uma nova partida de Sudoku. É possível inicializar o tabuleiro com configurações pré-definidas através de argumentos de linha de comando.
* **Inserir Número**: Adicione ou altere um número em uma célula específica do tabuleiro, desde que a posição não seja fixa.
* **Remover Número**: Limpe o valor de uma célula do tabuleiro, caso ela não seja uma posição fixa.
* **Visualizar Jogo Atual**: Exiba o estado atual do tabuleiro de Sudoku, com uma representação clara da grade.
* **Verificar Status do Jogo**: Analise o tabuleiro para identificar erros (números duplicados em linhas, colunas ou blocos 3x3) e o status geral do jogo (em andamento, com erros, ou concluído).
* **Limpar Jogo**: Resete o tabuleiro para seu estado inicial, ou limpe todas as entradas do usuário se o tabuleiro tiver sido iniciado vazio.
* **Finalizar Jogo**: Verifique se o Sudoku foi resolvido corretamente e se não há erros. Se sim, o jogo é encerrado com uma mensagem de sucesso.
* **Sair**: Encerra a aplicação a qualquer momento.

-----
💡 Conceitos Praticados


- Programação Orientada a Objetos (POO): Utilização de classes e objetos para modelar o tabuleiro (Board), as células (Space) e as interações do jogo, promovendo encapsulamento, herança e polimorfismo (se aplicável).

- Estruturas de Dados: Emprego de listas (ArrayList) e mapas (Map) para representar e gerenciar o tabuleiro do Sudoku e suas configurações.

- Manipulação de Stream API: Uso da API de Streams do Java para processamento eficiente de coleções, como na inicialização do tabuleiro a partir dos argumentos de linha de comando.

- Tratamento de Exceções: Implementação de mecanismos para lidar com entradas inválidas do usuário ou situações inesperadas, garantindo a robustez do programa.

- Design de Interface de Console: Criação de uma interface de usuário baseada em texto, com um menu interativo e feedback claro para o jogador.

- Validação de Entrada: Lógica para garantir que as entradas do usuário (linhas, colunas, números) estejam dentro dos limites válidos do jogo.

-----

## 💻 Tecnologias Utilizadas

* **Java JDK 21**
* **Intellij IDEA**
* **🔁 Git & GitHub**
-----

## 💡 Créditos
    
- Projeto realizado no Bootcamp GFT Start #7 - Java, da plataforma DIO, em parceria com a GFT.
- Aulas ministradas pela professor José Luiz.
