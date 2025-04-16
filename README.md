# 🧩 Sudoku em Java

Projeto de Sudoku desenvolvido em Java com duas versões: uma versão no terminal e outra com interface gráfica utilizando Swing. Este projeto foi desenvolvido como parte do módulo **"Criando um jogo do Sudoku em Java"**, oferecido pela **Digital Innovation One (DIO)** no bootcamp *Java Cloud Native*.

## 📌 Descrição

O objetivo deste projeto é permitir que o usuário jogue Sudoku diretamente pelo terminal ou por meio de uma interface gráfica intuitiva. O jogo já vem com números pré-estabelecidos para o usuário completar, mas é possível personalizar esses valores acessando a aba **"editar configurações"** da respectiva classe (`Main` ou `UIMain`).

## 🎮 Funcionalidades

- ✅ Modo texto (via terminal - classe `Main`)
- ✅ Modo gráfico (via Swing - classe `UIMain`)
- ✅ Validação do jogo em andamento
- ✅ Verificação do tabuleiro completo
- ✅ Botões interativos:
  - **Reiniciar**: limpa os valores inseridos pelo jogador.
  - **Verificar jogo**: valida o progresso atual e indica se há erros.
  - **Concluir**: verifica se o tabuleiro está completo e correto, parabenizando ou informando erros.
 
## 🚀 Como executar

1. Clone o repositório
2. Compile e execute a classe **Main** para jogar pelo terminal
3. Compile e execute a classe UIMain para jogar com uma Interface Gráfica
   - O tabuleiro será exibido em uma janela, com os botões de controle.

## 🛠 Tecnologias utilizadas

- Java 21 (Amazon Corretto)
- Swing (interface gráfica)
- IntelliJ IDEA

## ✏️ Personalização

É possível alterar os números iniciais do tabuleiro editando as configurações diretamente nas classes Main e UIMain, conforme preferir.

## 📄 Licença

Este projeto segue a licença MIT.
