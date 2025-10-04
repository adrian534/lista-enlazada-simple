package Listas;

/**
 *
 * 
 */
//lista enlazada simple
// joel adrian caballero lugo GTID141
//3/10/2025
public class Estudiante {
    private String nombre;
    private int edad;
    private double estatura;

    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }

    public void setEdad(int edad) {
        this.edad = edad;
    }

    public void setEstatura(double estatura) {
        this.estatura = estatura;
    }

    public int getEdad() {
        return edad;
    }

    public double getEstatura() {
        return estatura;
    }
    
    public Estudiante (int edad, String nombre, double estatura){
    
    this.edad = edad;
    this.estatura= estatura;
    this.nombre = nombre;
    }
    
    public Estudiante(){
    }
    
    
    public void escuchar(){
    }
    public void escribir(){
    }
    public void leer(){
    }
}
