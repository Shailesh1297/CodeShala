import java.util.Scanner;

/**
 *
 * @author UCHIHA
 */
public class WaterLess {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        short p1,p2,test;
        Scanner scan=new Scanner(System.in);
        test=scan.nextShort();
        while(test!=0)
        {
            long n=scan.nextLong();
            p1=scan.nextShort();
            p2=scan.nextShort();
            
 /*if 1L bottles are used then cost will be= amount of water needed(n)*price of 1L bottles
                case 1 Total=n*p1;
   if 2L bottles are used then cost for even amount of water(n%2==0) will be= amount of water needed(n)*price of 2L bottles
                                    for odd amount of water(n%2==1)
                  amount of water fullfilled by 2L bottles=n/2 and cost will be =(n/2)*price of 2L bottles
                  amount of water remaing filled by 1L bottles=(n%2==1 case odd) and cost will be =(n%2)*price of 1L bottles;
                case 2 Total=n%2*p1+n/2*p2;
                
          we will consider the lowest Total value from above cases
   */
       if(n*p1< n%2*p1+n/2*p2)
                System.out.println(n*p1); 
            else
                System.out.println(n%2*p1+n/2*p2);
            
         test--;   
        }
    }
    
}
