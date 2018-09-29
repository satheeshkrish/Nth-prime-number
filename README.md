# Nth-prime-number
public class Test{
  public static void main(String a[])
  {
    int input=100;
    int count=0;
    int i=2;
    
    while(count<input)
    {
      for(;i<i+1;i++)
      {
        if(isPrime(i))
           {
          
             count++;
             break;
           }
      }
      
          i=i+1;
    }
    System.out.println("the "+input+" Prime number is "+(i-1));
  }
  public static boolean isPrime(int x)
  {
    int i;
    for(i=2;i<x;i++)
    {
      if(x%i==0)
        break;
    }
    if(i==(x))
    {
      return true;
    }
    else
    return false;
  }
}
           
