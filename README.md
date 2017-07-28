# powNum
to calculate the power of a number in java
import java.util.*;
class Pow{
public static void main(String args[]){
long n,p,r=1;

Scanner s= new Scanner(System.in);
System.out.println("enter a number");
n=s.nextLong();
System.out.println("enter the power");
p=s.nextLong();
if(n>=0&&p==0)
{
  r=1;
}
else if(n==0&&p>=1)
{
  r=0;
}
else
{
  for(int i=0;i<p;i++)
  {
    r=r*n;
  }
}
System.out.println(n+"^"+p+"="+r);
}
}
