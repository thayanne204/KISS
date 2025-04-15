public class ParOuImpar {
    public static void verificarNumero(int numero) {
        if (numero % 2 == 0) {
            System.out.println("O número " + numero + " é par.");
        } else {
            System.out.println("O número " + numero + " é ímpar.");
        }
    }
     public static void main(String[] args) {
        verificarNumero(7);
        verificarNumero(10);
    }
}
