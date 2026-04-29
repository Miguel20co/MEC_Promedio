# Python

    notas = [4.5, 3.2, 2.8, 5.0, 3.9]
print("Notas del estudiante:")
suma = 0
mayor = notas[0]
menor = notas[0]

for n in notas:
    print(n)
    suma = suma + n
    if n > mayor:
        mayor = n
    if n < menor:
        menor = n

promedio = suma / len(notas)
print("Promedio:", promedio)
print("Nota mas alta:", mayor)
print("Nota mas baja:", menor)

print('------------------------------------------')


estudiantes = [[4.0, 3.5, 4.2], [3.0, 2.5, 3.8], [5.0, 4.8, 4.5], [2.1, 3.0, 2.9], [4.5, 4.2, 4.0]]

for i in range(5): 
    print("Estudiante", i + 1)
    notas = estudiantes[i]
    
    suma = 0
    mayor = notas[0]
    menor = notas[0]
    
    for n in notas:
        suma = suma + n
        if n > mayor: mayor = n






# Java

package mis_tareas;

public class MECPromedio {
	public static void main(String[] args) {
    double[] notas = {4.5, 3.2, 2.8, 5.0, 3.9};

    double suma = 0;
    double mayor = notas[0];
    double menor = notas[0];

    System.out.println("Notas:");
    for (int i = 0; i < notas.length; i++) {
        System.out.println(notas[i]);
        suma = suma + notas[i];
        
        if (notas[i] > mayor) {
            mayor = notas[i];
        }
        if (notas[i] < menor) {
            menor = notas[i];
        }
    }

    System.out.println("Promedio: " + (suma / notas.length));
    System.out.println("Mayor: " + mayor);
    System.out.println("Menor: " + menor);
}
}

---------------------------------------------------------
package mis_tareas;

public class MECPromedio5 {
	public static void main(String[] args) {
    
    double[][] clase = {
        {4.0, 3.5, 4.2},
        {3.0, 2.5, 3.8},
        {5.0, 4.8, 4.5},
        {2.1, 3.0, 2.9},
        {4.5, 4.2, 4.0}
    };

    for (int i = 0; i < 5; i++) {
        System.out.println("Estudiante " + (i + 1));
        double suma = 0;
        double mayor = clase[i][0];
        double menor = clase[i][0];

        for (int j = 0; j < 3; j++) {
            double nota = clase[i][j];
            suma = suma + nota;
            if (nota > mayor) mayor = nota;
            if (nota < menor) menor = nota;
        }
        System.out.println("Promedio: " + (suma / 3));
        System.out.println("Mayor: " + mayor);
        System.out.println("Menor: " + menor);
       
    }
}
}




        if n < menor: menor = n
            
    print("Promedio:", suma / len(notas))
