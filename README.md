# poweOfFive
package Exercise;
import java.util.Scanner;
public class beşinKuvvetleri {
    public static void main(String[] args) {

        int i , n ;

        Scanner input = new Scanner(System.in);
        System.out.print("Sınır sayısını giriniz : ");
        n= input.nextInt();

        for(i =1 ; i<= n; i++ ){
            if (i % 4 == 0){
                System.out.println(i);

            }
            if (i % 5==0 && i % 4 !=0)
                System.out.println(i);

        }
        
    }
}
