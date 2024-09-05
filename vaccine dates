import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
    public static String checkVaccineTiming(int D, int L, int R) {
        if (D < L) {
            return "Too Early";
        } else if (D > R) {
            return "Too Late";
        } else {
            return "Take second dose now";
        }
    }

    public static void main (String[] args) throws java.lang.Exception {
        Scanner scanner = new Scanner(System.in);

        // Read the number of test cases
        int T = scanner.nextInt();

        // Process each test case
        for (int i = 0; i < T; i++) {
            int D = scanner.nextInt();
            int L = scanner.nextInt();
            int R = scanner.nextInt();

            String result = checkVaccineTiming(D, L, R);
            System.out.println(result);
        }

        scanner.close();
    }
}
