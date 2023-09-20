# MukemmelSayi

import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		
		System.out.print("Sayi girin: ");
		int sayi = input.nextInt();
  
		int toplam = 0;
		
		for (int i = 1; i<sayi; i++){
			if (sayi % i == 0) {
				toplam += i;
			}
		}
		
		if (toplam == sayi) {
			System.out.println(sayi+ " mukemmel bir sayidir.");
		}
		
		else {
			System.out.println(sayi+ " mukemmel bir sayi degildir.");
		}
	}
}
