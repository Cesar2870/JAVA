# JAVA

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    Scanner cb = new Scanner(System.in);
    System.out.println("DIgite o valor do raio para descobrir a área do circulo");
  
    int raio = cb.nextInt();

    double area = 3.14 * (raio * raio);
 
    
    System.out.println("A área do circulo é: " + area);
  
 }
}
