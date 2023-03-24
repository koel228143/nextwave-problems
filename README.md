# nextwave-problems
import java.util.*;
class traiangle{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int a1 = sc.nextInt();
        int a2 = sc.nextInt();
        int a3 = sc.nextInt();
        if((a1+a2+a3)==180){
            System.out.println("It's a Triangle");
        }else{
            System.out.println("It's not a Triangle");
        }
    }
}
