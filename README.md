# ejercicio9


public class Main {

    public static void main(String[] args) {

    }

    class Persona {
        int Edad;
        String Nombre;

        public String getNombre() {
            return Nombre;
        }

        public void setNombre(String nombre) {
            Nombre = nombre;
        }

        int telefono;

        public Persona(int edad, String nombre, int telefono) {
            Edad = edad;
            Nombre = nombre;
            this.telefono = telefono;
        }
    }

    class Cliente extends Persona {

        public Cliente() {
            String Credito;
        }

    }

}
