# 2-lab
//1. Екі санның минимумын табу
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt(), b = sc.nextInt();
        if (a < b) System.out.println(a);
        else System.out.println(b);
    }
}
 */
//2. 
/*
import java.util.Scanner;
public class Main{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        if (n % 2 == 0) System.out.println("Жұп");
        else System.out.println("Тақ");
    }
}
 */
//3. 1-ден N-ге дейінгі қосынды
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt(), sum = 0;
        for (int i = 1; i <= n; i++) sum += i;
        System.out.println(sum);
    }
}
 */
//4. 
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for (int i = 1; i <= 10; i++)
            System.out.println(n + " * " + i + " = " + (n * i));
    }
}
 */
//5. Факториалды таб
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        long fact = 1;
        for (int i = 1; i <= n; i++) fact *= i;
        System.out.println(fact);
    }
}
 */
//6. 
/*
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String s = sc.nextLine();
        String vowels = "аәеиіоөұүуыэАӘЕИІОӨҰҮУЫЭ";
        int count = 0;

        for (char c : s.toCharArray()) {
            if (vowels.indexOf(c) != -1) {
                count++;
            }
        }
        System.out.println(count);
    }
}
 */
//7. Жолды кері шығару
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String s = sc.nextLine();
        StringBuilder sb = new StringBuilder(s);
        System.out.println(sb.reverse());
    }
}
 */
//8. Массивтегі максимумды табу
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        for (int i = 0; i < n; i++) arr[i] = sc.nextInt();
        int max = arr[0];
        for (int v : arr) if (v > max) max = v;
        System.out.println(max);
    }
}
 */
//9. 
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        int sum = 0;
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
            sum += arr[i];
        }
        System.out.println(sum);
    }
}
 */
//10. Массивтен элемент іздеу
/*
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        for (int i = 0; i < n; i++) arr[i] = sc.nextInt();
        int x = sc.nextInt();
        boolean found = false;
        for (int v : arr) if (v == x) { found = true; break; }
        System.out.println(found ? "Бар" : "Жоқ");
    }
}
*/
