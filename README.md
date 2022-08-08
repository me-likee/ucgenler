# ucgenler

Console.WriteLine("Merdiven İçin Bir Sayı Giriniz:");
int sayi2=int.Parse(Console.ReadLine());
for(int i=1;i<=sayi2;i++)//sayi kadar alt alta yazdırıyor
{
   for(int j=i;j<sayi2;j++)
    {
        Console.Write(" "); 
    }
    for (int x = 0; x < i; x++)
    {
        Console.Write("*");  
    }
   
   Console.WriteLine();
}
