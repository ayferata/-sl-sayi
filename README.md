# -sl-sayi
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner input= new Scanner(System.in);
        int n,k;

        System.out.print("üssü alınacak sayı: ");
        n= input.nextInt();
        System.out.print("üs alınacak sayı: ");
        k= input.nextInt();
        int total=1;
        // 3*4=3*3*3*3
        int i=1;
        while (i<=k){
            total*=n;
            i++;
        }
        System.out.println("cevap: "+total);



        }

    }
