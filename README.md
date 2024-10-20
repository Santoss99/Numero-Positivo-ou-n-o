import java.util.Locale;
import java.util.Scanner;

public class exercicio1 {

	public static void main(String[] args) {

		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);

		int x;
		x = sc.nextInt();
		
		if(x>=0) {
			System.out.println("não negativo	
		}
		else {
			System.out.println("numero negativo"+x);
		}
		

		sc.close();
	}
}
