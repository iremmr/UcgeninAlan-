# UcgeninAlan-
```
import java.util.Scanner;

public class Ucgenalan {
    public static void main(String[] args) {
        int a,b,c,cevre,u;
        double alan;

        Scanner input = new Scanner(System.in);
        System.out.print("1. Kenar uzunluğunu giriniz: ");
        a = input.nextInt();

        System.out.print("2. Kenar uzunluğunu giriniz: ");
        b = input.nextInt();

        System.out.print("3. Kenar uzunluğunu giriniz: ");
        c = input.nextInt();

        cevre = a + b + c;
        u = cevre/2;
        alan = Math.sqrt(u*(u-a)*(u-b)*(u-c));
        System.out.println("Alan = " + alan);


    }
}
```
[Patika.dev](https://app.patika.dev/iremr)
