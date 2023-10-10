# po.test
# Hello world!

static void zad1()
{
  Console.Write("Podaj promień:");
  double r = Double.Parse(Console.ReadLine());
  if (r<0)
  {
  Console.Writeline("Niepoprawne dane!")
  }
  [else
  {
  double pole = Math.PI*r*r;
  Console.WriteLine("Pole wynosi: {0:0.##}", pole);
  }]
}


  static void zad2()
  {
    Console.WriteLine("Podaj pierwszy bok: ");
    double a = Double.Parse(Console.ReadLine());
    Console.WriteLine("Podaj drugi bok: ");
    double b = Double.Parse(Console.ReadLine());
    double pole = a*b;
    Console.WriteLine("Pole wynosi: {0:0.##}", pole);
    if (a=b)
    {
    Console.Writeline("Prostokąt jest kwadratem")
    }
    [else
    {
    Console.Writeline("Prostokąt nie jest kwadratem")
    }]
   }
    
    
      
