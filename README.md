# herencia_abtracion-
trabajo
Ejercicio 1   Vehiculo y Bicicleta	Nivel 1
Crea una clase abstracta Vehiculo con el atributo marca y un método abstracto describir_transporte(). Crea una subclase Bicicleta que herede de Vehiculo, agregue el atributo num_cambios e implemente describir_transporte() imprimiendo la marca y el número de cambios. Instancia dos bicicletas de marcas distintas.
Instrucciones: Para cada ejercicio debes escribir: (1) la clase abstracta (usando ABC) con sus métodos abstractos, (2) la(s) subclase(s) que hereden e implementen dichos métodos, y (3) al menos un objeto de prueba con llamadas a los métodos. Recuerda importar ABC y abstractmethod del módulo abc.

Ejercicio 2   Habitacion, Reserva, Estandar y VIP	Nivel 3
Crea una clase Habitacion (numero, tipo, precio_noche). Crea una clase abstracta Reserva con atributos cliente, habitacion (objeto Habitacion) y noches, y métodos abstractos calcular_total() y confirmar(). Crea subclases ReservaEstandar (paga solo el costo de las noches) y ReservaVIP (agrega desayuno de $25.000 por noche). Cada subclase recibe un objeto Habitacion. Prueba reservando 3 noches en cada modalidad.

Ejercicio 3   Notificacion, Email y SMS	Nivel 2
Crea una clase abstracta Notificacion con el atributo destinatario y dos métodos abstractos: enviar() y formato_mensaje(). Crea dos subclases: NotificacionEmail (agrega asunto) y NotificacionSMS (agrega numero). Cada subclase hereda e implementa los métodos con su propio formato. Instancia una de cada tipo, genera el formato y envíalas.
