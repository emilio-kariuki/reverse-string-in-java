# reverse-string-in-java
how to reverse a string in java



import java.util.Scanner;

public class Reverse {
    public static void main(String arg[]){
        Rev obj = new Rev();
        obj.maned();

    }

}
class Rev {
    public void maned(){
        Scanner scanner = new Scanner(System.in);
        System.out.println("please Enter the string : ");
        String name = scanner.nextLine().toLowerCase();

        StringBuffer name_1 = new StringBuffer(name);

        String name_2 = name_1.reverse().toString();

        System.out.println(name_2);
    }
}
