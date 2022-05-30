# primenumber
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        String asalSayilar = "";
        for (int i = 1; i <= 11; i++) {
            int sayac = 0;
            for (int j = 1; j <= i; j++) {
                if (i % j == 0) {
                    sayac++;
                }
            }
            if (sayac == 2) {
                asalSayilar = asalSayilar + i + " ";
            }
        }
        System.out.println(asalSayilar);
    }
}
