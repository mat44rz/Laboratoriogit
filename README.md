Oigan papussss añadí una nueva cosa: 

Le metí la declaración del flujo de salida ofstream archivoSalida("output/archivoSalida.txt"); inmediatamente después de la lectura del archivo de entrada
Validación de apertura doble donde el condicional if original se actualizará a if (archivoEntrada.is_open() && archivoSalida.is_open()) para garantizar que la ejecución continúe solo si ambos documentos están accesibles   
La escritura en el ciclo que dentro del bucle while, le inserté la instrucción archivoSalida << linea << endl; para que cada línea de texto proveniente de archivoEntrada.txt se transcriba en el archivo de destino y se respete el salto de línea   
Y el mensaje de éxito es que agregué cout<<"Archivo copiado correctamente"<<endl; fuera del ciclo while para confirmar en la consola que el proceso de copiado finalizó   
