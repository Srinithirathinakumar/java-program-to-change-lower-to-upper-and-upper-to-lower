# java-program-to-change-lower-to-upper-and-upper-to-lower
java program to change lower to upper and upper to lower
import java.util.*;
public class Main
{
public static void main(String[] args) {
   Scanner sc = new Scanner (System.in);
String s=sc.nextLine();
for(int i=0;i<s.length();i++){
System.out.print((char)(s.charAt(i)^32));  
}
}
}
