# Arrays
Arrays problems 
ADDING VALUES TO AN ARRAY
import java.util.Arrays;
import java.util.Scanner;

public class Array {

  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    System.out.println("ENTER THE RANGE:");
    int a = sc.nextInt();
    int[] s = new int[a];
    for (int i = 0; i < a; i++) {
      s[i] = sc.nextInt();
    }
    System.out.print("[");
    for (int i = 0; i < a; i++) {
      System.out.print(s[i]);
      if (i < a - 1) {
        System.out.print(",");
      }
    }
    System.out.print("]");
  }
}
