# class1

 class Demo4
{
public static void main(String args[])
{		
System.out.println("welcome");
try
{
String S1=args[0];
String S2=args[1];
System.out.println("party");
int x=Integer.parseInt(S1);
int y=Integer.parseInt(S2);
System.out.println("happy birthday antra");
int z=x/y;
System.out.println("done");
}
catch(ArithmeticException  ee) 
{
System.out.println("plz donot enter zero");
}
catch(NumberFormatException  ee)
{
System.out.println("plz give number type data");
}
System.out.println("aree garba bhi chal raha he");
}

}
