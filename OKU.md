# -DEV
BİLGİSAYAR BÖLÜMÜNDE VERİLEN ÖDEVLERİ GİREN DE YARARLANSIN VE BENİMDE DEPOLAMA ALANINDA FAZLA YER KAPLAMASIN DİYE BURADAN PAYLAŞIYORUM...


 Klavyeden girlen 3 ürünün fiyatı 500 tl den fazla ise, 2. üründen %15 ve
 3. üründen %10 indirim uygulanacak kod



double d1, d2, d3, toplam;
Console.WriteLine("ilk değeri okut: ");
d1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("ikinci değeri okut: ");
d2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("üçüncü değeri okut: ");
d3 = Convert.ToDouble(Console.ReadLine());
toplam = d1 + d2 + d3;
if (toplam >= 500)
{
    d2 = d2 * 85 / 100;
    d3 = d3 * 90 / 100;
    toplam = d1 + d2 + d3;
    Console.WriteLine("sonuç" + toplam);
}
else if (toplam <= 500)
{
    Console.WriteLine("sonuç"+toplam);
}

Console.ReadLine();
