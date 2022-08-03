# Mukemmel-Sayi-Bulan-Program
Klavyeden girilen bir sayının mükemmel sayı olup/olmadığını bulan ve sayı mükemmel sayı ise ekrana “mükemmel sayıdır.” değilse “mükemmel sayı değildir.” ifadelerini ekrana yazan programı Java dilinde yazınız.

    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("Bir sayı giriniz :");
        int number = inp.nextInt();
        int result = 0, total = 0;

        for (int i = 1; i < number; i++) {

            if (number % i == 0) {
                total = i;
                result += i;
            }
        }

        if (result == number) {
            System.out.print(result + " mükemmel sayı ");
        } else {
            System.out.println(number + " Mükemmel sayı değil ");
        }

     }
    }
    
    
   
   
   ![image](https://user-images.githubusercontent.com/107626332/182567679-096d6ed0-a4fd-4434-9230-4aee7286b5bb.png)

   https://app.patika.dev/ahmetfurkan
