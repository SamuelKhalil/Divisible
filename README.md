# Divisible

package divisible;

/**
 *
 * @author khalil
 */
public class Divisible {
static final int three = 3;
static final int seven = 7;

    public static void main(String[] args) {
    
        divisible();
        
    }

    private static boolean CAT(int input){
      if (input%three == 0){ 
        System.out.print("CAT\n");	
      }
     return false;	 
    }
    private static boolean DOG(int input){
      if (input%seven == 0){ 
        System.out.print("DOG\n");	
      }
     return false;
     }
    private static boolean CAT_DOG(int input){
      if (input%three == 0 && input%seven == 0){ 
        System.out.print("CAT-DOG\n");	
      }
     return false;
    }
    private static void divisible(){
      for (int i = 1; i<100; i++) {
        if (CAT_DOG(i)|| CAT(i) || DOG(i)){
            } 
        else{ 
         System.out.print(i + "\n"); 
             }
            }
}
}
