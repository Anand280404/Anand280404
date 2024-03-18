import java.util.Scanner;
public class PG1{
    public static void main (String args[]){
        Scanner sc=new Scanner(System.in);
        int num, temp, count=0;
        System.out.println("Enter an integer value greater than 2");
        num = sc.nextInt();

        if(num<2){
            System.out.println("Invalid output");
        }else{

            temp=num;
            do
            {
                temp /=2;

                count++;
            }while(temp >=2);

            System.out.println("The number of times we need to divide" +num+ "by 2 before reducing to less than 2 is " + count);
        }
        

        }

        

    }
