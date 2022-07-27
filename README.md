import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s= new Scanner(System.in);
        int n1= s.nextInt();
        int n2= s.nextInt();
        int n3= s.nextInt();
        int ans= (n1+n2+n3)/3;
        System.out.print(ans);
    }
}
