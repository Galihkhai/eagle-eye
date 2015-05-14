![alt tag](http://7-themes.com/data_images/out/42/6913762-juventus-wallpaper.jpg)
import java.util.Scanner;
public class coba 
{
   public static void main(String[] khai)
   {
         Scanner in = new Scanner(System.in);
        System.out.println("Masukkan angka =");
        int n = in.nextInt();
        int [] angka = new int [n];
         for (int i = 0; i < angka.length; i++) {
            System.out.print("Masukkan angka ke "+(i+1)+" = ");
            angka[i]=in.nextInt();
     }
   }
    void urut(int [] angka)
    {
            for (int i = angka.length-1; i >= 0; i--)
            {
                for (int j = 0; j < i; j++) 
                {
                    if (angka[j]>angka[j+1])
                        
                }
            }
     }
   }
        
}
