# Operaci-n-Resta
package operacion_resta;

import javax.swing.JOptionPane;


public class Operacion_resta {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
int a=Integer.parseInt(JOptionPane.showInputDialog(null,"Inserte el primer numero "));
int b=Integer.parseInt(JOptionPane.showInputDialog(null,"Inserte el segundo numero"));

int resultado=a-b;

JOptionPane.showMessageDialog(null,"El resultado de la resta de " + a + " - " + b + " es: "+resultado);

