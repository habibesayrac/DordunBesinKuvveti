# DordunBesinKuvveti

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int num;
        Scanner input = new Scanner(System.in);
        System.out.println("Sınır Sayısını Giriniz: ");
        num = input.nextInt();

        for(int i= 1; i<=num; i*=4){
            if(i%4==0) {
                System.out.println(i);
            }
        }
        for (int j=1;j<=num;j*=5) {
            if (j % 5 == 0) {
                System.out.println(j);
            }
        }
    }
}
