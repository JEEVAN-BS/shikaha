class Asscii
{
   public static void main(String args[])
   {
     Scanner scan=new Scanner(System.in);
     String s=Scan.nextline();
     String str="sHQen";
     int len=str.length();
     asciiTOSentence(str,length);
}
}
class ass
{
  Static void asciiTOSentence(String str,int len)
  {
   int num=0;
   for(int i=0;i<len;i++)
   { 
    num=num*10+(str.charAt(i) -"0");
    if(num>=32 && num<=122)
    char ch=(char) num;
    System.out.print(ch);
    num=0;
}
}
}
     
