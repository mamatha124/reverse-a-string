# reverse-a-string
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        String s= "hello world";
        String str[]=s.split(" ");
        String k="";
        for(int i=str.length-1;i>=0;i--){
            k=k+str[i];
            k=k.trim();
            k=k+" ";
        }
        System.out.println(k.trim());
    }
}
