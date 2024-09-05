import java.util.*;

class Codechef {
    public static void main (String[] args) throws java.lang.Exception {
        Scanner sc = new Scanner(System.in);
        
        int T = sc.nextInt();  // Number of test cases
        
        for (int i = 0; i < T; i++) {
            int A = sc.nextInt();  // Chef's initial net worth
            int B = sc.nextInt();  // Target net worth
            int X = sc.nextInt();  // Yearly increase
            int t = 0;  // Years counter
            
            while (A < B) {
                A += X;
                t++;
            }
            
            System.out.println(t);  // Print only the number of years
        }
        
        sc.close();
    }
}
