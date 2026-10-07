# ProjetoBancoDeDados
Projeto experimental desenvolvido em Java para a criação e gerenciamento de um banco de dados com a utilização de Interface Gráfica do Usuário (GUI).

O projeto apresentado consiste em um projeto simples realizado com o intuito de familiarização com a linguagem Java a partir da implementação de um Banco de Dados (mais precisamente, SQLite), utilizando uma Interface Gráfica do Usuário (GUI) desenvolvida com a biblioteca JavaFX.

Para rodar o Projeto de Banco de Dados, siga os seguintes passos:

#1 Instalação do Java Development Kit (jdk) na sua máquina:
- Caso não tenha o Java instalado na sua máquina, a instalação pode ser feita no site da Oracle;
- A versão utilizada no projeto é a jdk-22;
- Após a instalação, execute o arquivo e adicione suas respectivas variáveis ao path do Windows.

#2 Faça o download do arquivo .zip

#3 Extraia o arquivo

#4 Adicione a variável de ambiente:
  CLASSPATH
  .;sqlite-jdbc-3.46.0.0.jar;slf4j-api-1.7.13.jar;slf4j-simple-1.7.13.jar
    OBS.: Teste se a variável está corretamente configurada
      Comando: echo %CLASSPATH%
      Saída: .;sqlite-jdbc-3.46.0.0.jar;slf4j-api-1.7.13.jar;slf4j-simple-1.7.13.jar

#5 Execução do programa:
- Primeiramente, no terminal do Windows, dirija-se à pasta que contém os arquivos por meio do método cd
- Agora, execute o arquivo "CriadorTabela.java", que irá inicializar o banco de dados e criar a tabela de testes por meio do seguinte código:
  java CriadorTabela
- Depois execute o arquivo "ProdutoGUI.java", que consiste na interface gráfica da aplicação.
  Você pode fazer isso por meio do seguinte código:
    java --module-path "C:\Java\javafx-sdk-22.0.1\lib" --add-modules javafx.controls ProdutoGUI

Agora você poderá testar o programa experimental de gerenciamento de banco de dados.
