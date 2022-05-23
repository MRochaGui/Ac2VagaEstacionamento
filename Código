package application;

import java.util.Scanner;

public class Ac2Estacionamento {

	public static void main(String[] args) {

        Scanner ler = new Scanner(System.in); // se for idoso, gestante, ou deficiente fisico podera estacionar na vaga
                                                // especial.

        int ido, ges, def,pes;

        System.out.println("Por favor digite:\n1 se você for idoso.\n2 se você for gestante.\n3 se você for deficiente físico.\n4 se não se enquadrar em nenhuma das opções acima.");
        pes = ler.nextInt();            //< armazenar input.  ^Pedir pra pessoa escolher entre 4 opções.
        ler.close(); //economizar memoria.

        ido = 1;  
        ges = 2;
        def = 3;

        if (pes == ido || pes == ges || pes == def) {   //Se pessoa for igual a idoso, ou pessoa for igual gestatente, ou pessoa for igual deficiente faça:
            System.out.println("Você pode usar a vaga de estacionamento especial");
        } else   //Se não, faça.
            System.out.println("Você não pode usar a vaga de estacionamento especial");

    }

}
