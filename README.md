Implementación de Patrones de Integración
================================================

Diagrama del Demostrativo de los Patrones de Integración


	                                                                                          Barista
	                                                                     BebidasCalientes ____________________
	                                                                    |==========| -->|                    |
	                     ordenes                   bebidas               /                | prepareHotDrink()  |
    Lugar de Ordenamiento ->Cafes->|======|->DivisorBebidas->|======|->RouterBebidas                  |                    |
	                                                                   \ BebidasFrias     | prepareColdDrink() |
	                                                                    |==========| -->|                    |
	                                                                                    |____________________|
	
	                                                Leyenda: |====| - Canales


## Instrucciones para correr el Demostrativo

Para correr el ejemplo solo ejecute la clase CafeDemoApp dentro de la carpeta  src/main/java/org.springframework/annotation


