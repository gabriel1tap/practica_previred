# practica_previred

public class previred{
	public static void main(String[] args) {
		//Declaro una variable tipo String llamada variable1, con el valor "Previred".
		String variable1 = "Previred";
		//Imprimiendo por consola la variable1.
		System.out.println(variable1);
		//Utilice la clase StringBuilder para crear la variable2 y utilizar el metodo reverse para invertir la variable 1.
		StringBuilder variable2 = new StringBuilder(variable1);
		//Aqui reemplazare el valor de la variable1.
		//Utilizo toString para transformar la variable2 a tipo de dato String.
		variable1 = variable2.reverse().toString();
		//Imprimiendo por consola la variable1.
		System.out.println(variable1);
	}
}
