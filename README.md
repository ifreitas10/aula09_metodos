/**
 * Created by aluno on 12/04/2018.
 */
import javax.swing.*;
//classe Cachorro
/*public class aula09{
    public static void latir(int numVezes){
        for (int i = 1; i <= numVezes; i++){
            System.out.println("au!");
        }
    }
    //Aqui inicia o metodo main
    public static void main (String[] args){
        System.out.println("Meu cachorro" + " vai latir!");
        latir(3);
        System.out.println("Meu cachorro" + " latiu!");
    }
}*/

//classe Pessoa
/*public class aula09{
    public String nome;
    public int anoNascimento;
    public int anoAtual;

    public static int minhaIdade(){
        return 2018 - 1997;
    }

    public static void main(String[] args){
        System.out.println("A minha idade é:");
        int resposta = minhaIdade();
        System.out.println(resposta);
    }
}*/

//
/*public class aula09{
    public static void envia(){
        recebe(12, 34);
    }
    public static void recebe(int x, int y){
        int z = x + y;
        System.out.println(z);
    }

    public static void main (String[] args){
        envia();
    }
}*/

public class aula09{
    //Escreva um programa que leia dois vetores, A e B, de 5 inteiros. Crie um vetor C de 5 inteiros e faça:
    //Se o elemento de A for par, o respectivo elemento de C deve ser o produto do elemento A com o de B;
    //Se for ímpar, o respectivo elemento de C deve ser A elevado B;
    public static void main(String[] args){
        int[] vetorA = new int[5];
        int[] vetorB = new int[5];
        int[] vetorC = new int[5];
        int indice;

        for(indice = 0; indice<=1; indice++){
        vetorA[indice] = Integer.parseInt(JOptionPane.showInputDialog("Digite um inteiro"));
        vetorB[indice] = Integer.parseInt(JOptionPane.showInputDialog("Digite um inteiro"));
            if(vetorA[indice] % == 0){
                
            }
        }

    }
}
