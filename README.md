1. A função da máquina virtual java (JVM) é executar código compilado Java. Seu uso faz com que seja possível executar os programas de forma igual em diferentes dispositivos.
  

2. JRE se refere a Java Runtime Environment que é software capaz de executar Java, enquanto que JDK se refere a Java Development Kit que é o conjunto de ferramentas necessárias para criar um programa em Java. Dessa forma, é preciso ter o JRE, mas não o JDK, para executar os programas criados.


3. `Questao3.java`


4. `
   Error: Could not find or load main class Questao3
   Caused by: java.lang.ClassNotFoundException: Questao3
   `  
Ou seja, erro por não encontrar o arquivo para executar.


5. `
   Error: Main method not found in class Questao3, please define the main method as:
   public static void main(String[] args)
   or a JavaFX application class must extend javafx.application.Application
   `  
Ou seja, erro por não encontrar a função main para executar o programa.


6. `Questao6.java`


7. Nem mesmo compila:  
   `
   questao6diferente.java:1: error: class, interface, or enum expected  
   PUBLIC CLASS QUESTAO6{  
   ^  
   questao6diferente.java:4: error: class, interface, or enum expected  
   SYSTEM.OUT.PRINTLN("UNDEFINED");  
   ^  
   questao6diferente.java:5: error: class, interface, or enum expected  
   }  
   ^  
   3 errors  
   `  
O que significa que o programa não pôde ser compilado porque as palavras em maiúsculo não foram reconhecidas.


8. `
questao6diferente.java:1: error: class Questao6 is public, should be declared in a file named Questao6.java
public class Questao6 {
^
1 error
`  
Um erro causado por o nome do arquivo não ser o mesmo do da classe.