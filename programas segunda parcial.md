//una sola linea//
/*
comentarios
en 
bloque
*/

//Encapsulacion

void main() {
User usuario = User();
User usuario=User("Alfredo",15); //constructor
print(usuario);
print(usuario.nombre);
print(usuario.edad);

User usuario = User();
usuario.nombre= "Alfredo";
usuario.edad= 25;

usuario._edad=25;
usuario.nombre="Alfredo";
usuario.reporteUser();
print(usuario.nombre);
print(usuario.edad);
usuario.reporte();

final usuario =User();
usuario.nombre= "Alfredo";
print(usuario.nombre);
print(usuario.edad);
usuario.reporte();

User usuario= User(nombre:"Alfredo", edad: 25);
print(usuario.getNombre);
print(usuario._edad);

User usuario2 = User();
print(usuario);
usuario2._edad=22;
usuario2.nombre="Diana";
usuario2.reporteUser();

}
//clase que representa un usuario
class User{
  String? _nombre;
  int? _edad;
  metodo que imprime un usuario
  void reporteUser(){
  print(_edad);
  print(_nombre);
  }

  String? nombre;
  int? edad;
  void reportUser(){
    print("Nombre: $nombre");
    print("Edad: $edad años");

  String? _nombre;
  int? _edad;

  void set nombre(String nombre){
    _nombre= nombre;  
  }  

  void set edad(int edad){
    _edad=edad;
  }
  String get nombre{
    return _nombre!;
  }
  int get edad{
    return _edad!;
  }
  void reporte(){
    print("nombre: $_nombre");
    print("edad: $_edad años");
   }
}  
  
    void main(){}
   print(nombre);
   print(edad)
   user(String nombre, int edad){
   this._nombre =nombre;
   this._edad =edad;
   short hand
    User(this._nombre, this._edad);
   
 

  void set nombre(String nombre)=>  _nombre = nombre;
  void set edad(int edad)=> _edad = edad;

  String get nombre => _nombre!;
  int get edad=>  _edad!;
  
void reporte(){
  print("nombre: $_nombre");
  print("edad: $_edad años");
}

  //argumentos o propiedades nombrada
  user({this.nombre, this.edad)
  void set setNombre(String nombre) =>  nombre = nombre;
  
  void set getEdad(int edad) => edad = edad;
  String get getNombre => nombre!;
  int get getEdad=>  Edad!;
  
   User(String nombre, int edad){
    this._nombre=nombre;
    this._edad = edad;
  }
  String? get nombre => _nombre;
  int? get edad => _edad;
}



void main() {
  Vehiculo miFord = Vehiculo();
  print(Vehiculo);
  
  miFord.setNoLlantas = 6;
  miFord.setMarca = "super dutty";
  miFord.setModelo = 2022;
  miFord.setColor = "gris, negro";
  print(miFord.getNoLlantas);
  print(miFord.getMarca);
  print(miFord.getModelo);
  print(miFord.getColor);
}

  class Vehiculo{
    int? _noLlantas;
    String? _marca;
    int? _modelo;
    String? _color;

   // Vehiculo(this._noLlantas, this._marca,this._modelo,this._color);

    void set setNoLlantas(int NoLlantas) =>  NoLlantas = NoLlantas;
    void set setMarca(String Marca) =>  Marca = Marca;
    void set setModelo(int Modelo) => Modelo = Modelo;
    void set setColor(String Color) => Color = Color;

    int get getNoLlantas => _noLlantas!;
    String get getMarca => _marca!;
    int get getModelo => _modelo!;
    String get getColor => _color!;

}
