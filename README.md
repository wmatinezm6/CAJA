# CAJA

//PROGRAMA PARA SABER LAS DIMENCIONES DE UNA CAJA
//UTILIZANDO CONTRUCTORES Y METODOS

package Cubo;

/**
 *
 * @author WILDER M
 */
public class caja {
    
    //atributos de la caja
    
    int alto;
    int ancho;
    int profundidad;
   
    public caja(){
        
        
    }
    //segundo constructor
    
    public caja(int alto,int ancho,int profundidad){
        
        this.alto=alto;
        this.ancho=ancho;
        this.profundidad=profundidad;
        
    }
    



public void mostrarvolumen(){


System.out.println("el volumen es: "+ancho*alto*profundidad);

}
}




//MEIN CLAS

package Cubo;
import java.util.Scanner;
/**
 *
 * @author WILDER M
 */
public class caja1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
        
        // clase caja
        // nombre de objeto op
        
        Scanner in=new Scanner(System.in);
        
        caja op=new caja();
        caja op2=new caja();
        
        System.out.println("ingrese el ancho de la caja");
        op2.ancho=in.nextInt();
        
        System.out.println("ingrese la altura de la caja");
        op2.alto=in.nextInt();
        
        
        System.out.println("ingrese la profundidad de la caja");
         op2.profundidad=in.nextInt();
         
         
         op2.mostrarvolumen();
        
      
    }
    
}



