import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int max = sc.nextInt();
        for (int i = 0; i < 3; i++) {
            int x = sc.nextInt();
            if (x > max) max = x;
        }
        System.out.println(max);
    }
}
