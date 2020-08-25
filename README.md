# price
import java .util.*;
class price
{
public static void main (String args [])
{
Scanner in= new Scanner (System.in)
int cp,sp,gain,loss;
System.out.println("enter cost and selling price of product");
cp= in.nextInt();
sp=in.nextInt();
if(sp>cp)
{
gain=sp-cp;
System.out.println("gain will be"+gain);
}
else
{
loss= cp-sp;
System.out.println("loss will be"+loss);
}
}
}
