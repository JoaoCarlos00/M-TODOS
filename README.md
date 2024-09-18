# MÉTODOS
Lista de Exercícios da ETAPA 2 da AC1 de POO
Escreva um método que mostra se um número é positivo ou negativo. Considere o zero positivo.
import java.util.Scanner;

public class NumeroPositivoNegativo {
    public static void main(String[]args); {

    Scanner scanner = new scanner(System.in);

    System.out.println("Digite um número:");
    int numero = scanner.nextInt();

    if (numero == 0) {
    System.out.println("Positivo");
    } else if (numero > 0) {
    System.out.println("Positivo");
    } else {
    System.out.println("Negativo");
    }
    scanner.close();
}
}
    
Escreva um método recebe 3 números e informa a média aritmética;
import java.util.Scanner;

public class MediaAritmetica {
    public static void main(String[]args); {
    double numero;
    double numero 2;
    double numero 3;
    double media;
    Scanner scanner = new scanner(System.in);

    System.out.println("Digite o primeiro número:");
    numero = scanner.nextDouble();

    System.out.println("Digite o segundo número:");
    numero2 = scanner.nextDouble();

    System.out.println("Digite o terceiro número:");
    numero3 = scanner.nextDouble();

    media = (numero + numero2 + numero3)/3;
    System.out.println("A média aritmética: " + media);

}
}
Escreva um método que recebe três números e retorna o maior.
import java.util.Scanner;

public class MaiorNumero {
    public static void main(String[]args); {
    int numero;
    int numero 2;
    int numero 3;
    Scanner scanner = new scanner(System.in);

    System.out.println("Digite o primeiro número:");
    numero = scanner.nextInt();

    System.out.println("Digite o segundo número:");
    numero2 = scanner.nextInt();

    System.out.println("Digite o terceiro número:");
    numero3 = scanner.nextInt();

    if (numero > numero2 && numero > numero 3) {
    System.out.println("O maior número é: " + numero);
    }
    else if (numero > numero2 && numero < numero3) {
    System.out.println("O maior número é: " + numero3) 
    }
    else if (numero < numero2 && numero2 < numero3) {
    System.out.println("O maior número é: " + numero3) 
    }
    else if (numero < numero2 && numero2 > numero3) {
    System.out.println("O maior número é: " + numero2) 
    }
}
}
Escreva um método que recebe dois números, a e b, e retorna ab.
import java.util.Scanner;

public class A_elevado_a_B {
    public static void main(String[]args); {
    int numero;
    int numero 2;
    int retorno;
    Scanner scanner = new scanner(System.in);

    System.out.println("Digite o primeiro número:");
    numero = scanner.nextInt();

    System.out.println("Digite o segundo número:");
    numero2 = scanner.nextInt();

    retorno = (numero*numero2);
    System.out.println(retorno);

}
}
Escreva um método que recebe uma quantidade de minutos e retorna o equivalente em horas e minutos.
Por exemplo: 90 min = 1 hora e 30 minutos
import java.util.Scanner;

public class Horas_e_Minutos {
    public static void main(String[]args); {
    double numero;
    double retorno;
    double retorno2;
    Scanner scanner = new scanner(System.in);

    System.out.println("Digite a quantidade de minutos à ser convertido em horas: ");
    numero = scanner.nextDouble();

    retorno = numero % 60;
    retorno2 = (numero - retorno) / 60;

    System.out.println(retorno2 + "Horas(s) e " + retorno + "minuto(s)");

}
} 
Escreva uma função que retorna o fatorial de número informado por parâmetro
