# Atividades-programa-o-faculdade-java
atividades feitas em java

import java.util.Scanner;

public class Tic {

	public static void main(String[] args) {

		Scanner sc = new Scanner(System.in);

		System.out.println("informe o primeiro valor:");
		int n1 = sc.nextInt();

		System.out.println("informe o segundo valor:");
		int n2 = sc.nextInt();

		int cl = n1 + n2;

		if (cl >= 20) {
			cl = cl + 8;

			System.out.println("a soma + 8 deu:" + cl);
		}

		else {
			cl = cl - 5;
			System.out.println("a soma - 5 deu:" + cl);
		}

		sc.close();

	}

}
