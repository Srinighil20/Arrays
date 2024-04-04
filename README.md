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

ODD NUMBERS AND TOTAL OF ARRAY ------------------------------------------------------------------------------------------------------
public class Array {
  public static void main(String[] args) {
    int x = 0;
    int[] a = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };
    System.out.print("THE ODD NUMBERS ARE:");
    for (int i = 0; i < a.length; i++) {
      if (a[i] % 2 == 1) {
        System.out.print(" " + a[i] + " ");
      }
      x = x + a[i];
    }
    System.out.println();
    System.out.println("THE TOTAL VALUE OF THE ARRAY:" + " " + x);
  }
}
