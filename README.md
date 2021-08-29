# ejercicio6
actividad
package ejercico6;

/**
 *
 * @author PC
 */
import java.util.Scanner;
public class Ejercico6 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner lc = new Scanner (System.in);
        int peso;
        int altura;
        int BMI;
        
        System.out.print("Ingrese el Peso\n");
        peso =lc.nextInt();
        System.out.print("ingrese la altura\n");
        altura =lc.nextInt();
        
        BMI = (altura*altura)/peso;
        
        System.out.println("El valor del BMI es:"+BMI);  // TODO code application logic here
    }
    
}
