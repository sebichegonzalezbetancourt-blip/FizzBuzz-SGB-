import java.util.Scanner; 

public class FizzBuzz {


    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        while (true) {
            System.out.print("Ingrese el numero o digite 0 para salir del programa: ");
            int n = sc.nextInt();


        if (n % 3 == 0 && n % 5 == 0) {
                System.out.println("FizzBuzz");
            } 
            else if (n % 3 == 0) {
                System.out.println("Fizz");
            } 
            else if (n % 5 == 0) {                                                                
                System.out.println("Buzz"); 
            } 
            else {
                System.out.println(n + " no es múltiplo de 3 ni de 5");
            }

            
            if (n == 0) {
                System.out.println("Game Over.");
                sc.close();
                break;
            }

            System.out.println(); 
        }
    }
}
