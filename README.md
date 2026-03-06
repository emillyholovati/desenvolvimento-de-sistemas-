# desenvolvimento-de-sistemas-
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
       Scanner scanner = new Scanner (System.in);
      
        int quant_horas, quant_minutos, quant_segundos, total_segundos;
        
        System.out.print("informe quantidade de horas: ");
        quant_horas = scanner.nextInt();
        
        System.out.print("informe quantidade de minutos: ");
        quant_minutos = scanner.nextInt();
        
        System.out.print("infrome quantidade de segundos: ");
        quant_segundos = scanner.nextInt();
        
        total_segundos = quant_segundos + quant_minutos * 60 + quant_horas * 3600;
        
        System.out.print("Total: %d ", total_segundos);
      
       
       scanner.close();
    }
}
