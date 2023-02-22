# DortKatlariniTopla
www.patika.dev
--------------------


import java.util.Scanner;

public class TekSayilarinToplami {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		
		int toplam =0;
		int sayi;
		
		do
		{
			System.out.println("Bir sayi giriniz");
			 sayi = scanner.nextInt();
			 
			 if(sayi%2 ==0 && sayi%4 ==0)
			 {
				 toplam += sayi;
			 }
		}
		while(sayi%2 ==1);
		
		System.out.println(toplam);
	}
	
	
}
