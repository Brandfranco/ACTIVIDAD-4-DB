# ACTIVIDAD-4-DB
CASO DE PRUEBA


CASO DE PRUEBA ID 01 

Paso 2: Descripción
En esta prueba se realizará la creación de 3 nodos en mongo BD para verificar el correcto funcionamiento de replicación y así asegurar la funcionabilidad de disponibilidad de los datos 24/7 aumentando la fiabilidad, rendimiento y seguridad de todos los datos en una posible caída del servidor.
Paso 3: Supuestos y condiciones previas

Se requiere  insertar datos en una colección de un BD ya creada y verificar que se respalden en un nodo segundario asegurando así la réplica.
Paso 4: Datos de prueba
testDB.arbitro.insert(
{
id: "4",
nombre : "sneider ",
 cedula: " 1090506954 ",
});

Paso 5: Pasos a ejecutar
1.	Crear 3 nodos.
2.	Introducir datos en una colección en el nodo primario.
3.	Generar un error en el nodo primario.
4.	Verificar que los datos se replicaron en el nodo segundario.
Paso 6: Resultado Esperado
El resultado del caso de prueba, fue exitoso como se puede evidenciar en las evidencias de la ejecución, replica exitosa.
