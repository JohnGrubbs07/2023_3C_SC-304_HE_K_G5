# ProyectoEstructura

<img width="364" alt="Captura de pantalla 2023-11-21 a la(s) 19 45 13" src="https://github.com/JohnGrubbs07/2023_3C_SC-304_HE_K_G5/assets/123349802/3984f0ed-b102-4e22-a6eb-a495a0de382d">

<img width="486" alt="Captura de pantalla 2023-11-21 a la(s) 19 45 42" src="https://github.com/JohnGrubbs07/2023_3C_SC-304_HE_K_G5/assets/123349802/4889531b-54a2-4450-85e2-3bf8c625aa41">


Este proyecto se va a basar de un tren que pasa por estaciones de las diferentes provincias de costa rica, esto va a funcionar por medio de estructura de base de datos, utilizaremos lo que seria Pilas, Colas, Listas Circulares Dobles.

Menu: El menu trae lo que serian las opciones: 
1-Agregar Pasajeros
2-Info de paradas
3-Informes generales
4-Cargar Pasajeros de Archivo
5-Salir

Opcion 1: Al entrar en esta opcion el sistema le pedira al usuario usuario primeramente el nombre completo, luego le pedira la edad, luego pedira en que estacion va a partir, luego le pregutara a que estacion va a ir y ya al final le preguntara si tiene alguna discapacidad.

Al poner todo esto el sistema por medio de unos ifs va a separar a los pasajeros dependiendo de 2 cosas: "Lugar de salida y Discapacidad", al obtener estos resultados va a separar en filas para entrar al vagon cuando llegue. Cada estacion tiene dos filas, una para discapacitados y otra para los demas. Al llegar el vagon llamara un metodo de vagon que primero revisa si hay personas que se bajan ahi y si si las baja y luego monta a las personas que estan en la fila solo si hay campo en el vagon.

El sistema en todo momento enseña en la consola la informacion de la estacion en a que esta, tambien las personas en la fila y enseñara las personas que se bajan del vagon.

Opcion 2: En esta opcion mostrara una info genenal sobre cuantas personas se han bajado del tren en total, no es nada sofisticado, solo es un informe.

Opcion 3: En este apartado saldran informes de todo, desde personas que se han bajado, personas que se han subido, dinero generado y kilometro recorridos.

Opcion 4: Esta opcion lo que va a hacer es que por medio de un archivo ini cargar pasajeros directamente a la fila de las direferentes estaciones.

Opciones 5: Esta opcion es una simple opcion de salir
