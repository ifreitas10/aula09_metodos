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

public class aula09 {

    public static int[] criaPreencheVetor(){
        int[] vetor = new int[5];

        for (int indice = 0; indice < 2; indice++){
            vetor[indice] = Integer.parseInt(JOptionPane.showInputDialog("Digite um número"));
        }
        return vetor;
    }
    public static double[] calcularVetorFinal(double[] primeiroVetor, double[] segundoVetor){
        double[] vetor = new double[5];

        for (int indice = 0; indice < 2; indice++){
            if (primeiroVetor[indice] % 2 == 0){
                vetor[indice] = primeiroVetor[indice] * segundoVetor[indice];
            } else{
                vetor[indice] = Math.pow(primeiroVetor[indice], segundoVetor[indice]);
            }
        }
        return vetor;
    }
    public static void menuDoPrograma(){
        String resposta = JOptionPane.showInputDialog("Deseja continuar? Sim/Não");

        if (resposta.equals("Sim")) {
            iniciarPrograma();
        } else {
            System.out.println("Saiu");
        }
    }

    public static void iniciarPrograma() {
        int[] vetorA = new int[5];
        int[] vetorB = new int[5];

        vetorA = criaPreencheVetor();
        vetorB = criaPreencheVetor();
        

        for (int i = 0; i <= 1; i++) {
            for (int indice = 0; indice < 2; indice++) {
                System.out.println("Valor do VetorA: " + vetorA[indice]);
            }
            System.out.println("--------------------");
            for (int indice = 0; indice < 2; indice++) {
                System.out.println("Valor do VetorB: " + vetorB[indice]);
            }
        }
        menuDoPrograma();
    }

    public static void main(String[] args) {
        iniciarPrograma();
    }
}
