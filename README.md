# java-teksayilarintoplami-iftve4unkatlari
java-teksayilarintoplamiçiftve4unkatlari

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int k, total = 0;

        Scanner input = new Scanner(System.in);

        do {
            System.out.print("Sayı giriniz : ");
            k = input.nextInt();
            if (k % 2 == 0 && k % 4 == 0){
                total += k;
            }
        } while ( k >= 4);
        System.out.println("Total : " + total);
    }
}
