# Atividade-Java
Célula: do rock
3. Faça um programa que receba a idade de oito pessoas, calcule e mostre:
a) a quantidade de pessoas em cada faixa etária; 
b) a porcentagem de pessoas na primeira faixa etária com relação ao total de pessoas. 
c) a porcentagem de pessoas na última faixa etária com relação ao total de pessoas






4. Faça um programa que receba um número, calcule e mostre a tabuada desse número. 
package Tabuada.com;

import java.util.Scanner;

public class ClassTabu {

  public static void main(String[] args) {
   
   int num, i = 0;
   
   Scanner ler = new Scanner(System.in);

   System.out.print("Informe um valor número qualquer que seja inteiro: ");
   num = ler.nextInt();

    for(; i <= 10; i++) {
       System.out.printf("%d x %d = %d\n", num, i, (num * i));
  }
}

}




5. Faça um programa que mostre as tabuadas dos números de 1 a 10.
import java.util.Scanner;

public class Tabuada {
    public static void main(String[] args) {
        int valor;
        Scanner teclado = new Scanner(System.in);
                System.out.println("digite um valor: ");
                valor=teclado.nextInt();
                
                for (int i = 0; i < 10; i++) {
                    System.out.println(valor + (valor*i));
            
        }
    }
}




