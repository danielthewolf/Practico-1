Practico-1
==========

punto 1

/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */
package principall;

/**
 *
 * @author Administrador
 */
public class Principall {

    public static void main(String[] args) {
        
        String v1 = "julian";
        String v2 = "lucas";
        String aux;
        String aux2;
      
        
        
         if (v1.length() <= 6  & v2.length() <= 6){
                       

               System.out.println("cadena1: "+v1);  
                System.out.println("cadena2: "+v2);
                 
                aux = v1;
                aux2 = v2;
                
                v1=aux2;
                v2=aux;
                 
               System.out.println("cadena1: "+v1);  
                System.out.println("cadena2: "+v2);            

           }
        else{
             System.out.println("Error de longitud ");
             
             }
         
    }
}
