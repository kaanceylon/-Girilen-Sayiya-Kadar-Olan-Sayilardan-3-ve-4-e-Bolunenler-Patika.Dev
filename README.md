# -Girilen-Sayiya-Kadar-Olan-Sayilardan-3-ve-4-e-Bolunenler-Patika.Dev
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int k,i=0;

        Scanner input = new Scanner(System.in);
        System.out.println("Bir sayı giriniz : ");
        k = input.nextInt();


        while (i <= k){
            i++;
            if (i % 3 ==0 ){
                if( i % 4 == 0){
                    System.out.println("Cevap : " + i);
                }
            }
        }


        }


    }
