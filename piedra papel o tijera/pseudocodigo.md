int oportunidades3
string movordenador // movimiento de la computadora
string movjugador // movimiento del jugador
int winmovordenador
int winmovjugador
bool

{

 class PiedraPapelOTijera
 {

  random rand=new random();

  
  console.WriteLine("selecciona el valor de jugada del usuario"):
  console.WriteLine("\t1.- Piedra");
  console.WriteLine("\t2.- Papel");
  console.WriteLine("\t3.- Tijera");
  console.WriteLine("\t: ");

  do
{ 
  jugada_del_usuario = 