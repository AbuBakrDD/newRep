import java.util.Scanner;
public class Main {
public static void main (String [] args) {
Scanner sc = new Scanner (System.in);
double result = 0;
while (sc.hasNext()) {
if (sc.hasNextDouble()) {
double d = Double.parseDouble(sc.next());
result += d;
} else {
continue;
}
}
System.out.printf("%.6f", result);
}

}
