# Projecto 1
Universidad de las Fuerzas Armadas Espe

Asignatura: Fundamentos de Circuitos Eléctricos

Docente: Ing. Darwin Alulema

Integrantes: JEAN PIERRE MERA GUZMAN -MICHAEL PATRICIO ANDRANGO CAMPUEZ -JOSE MAURICIO FUEREZ ARIAS

Parcial: 1

Projecto 1: TEMA: Led nocturno automático

2 OBJETIVOS

2.1 Objetivo General:

Realizar un proyecto en protoboard utilizando materiales electricos.

2.2 Objetivos especificos:

-construir un circuito detector de luminosidad.

-conocer el funcionamiento de cada uno de los componentes dentro de un circuito.

2.3 Marco teorico

Con los conocimientos adquiridos en la cátedra de circuitos electricos, durante el cursado de la materia se seleccionó un proyecto sencillo que se 
pueda armar en una placa experimentor y que funcione correctamente.

El proyecto seleccionado es un circuito sencillo que enciende y apaga una luz mediante un sensor que cuando disminuye la luz ambiente se enciende y cuando la 
luz ambiente es mayor, se apaga. Como aplicación resulta un montaje ideal para quien llega a casa de noche y desea encontrar las luces encendidas o también 
para quien no puede estar en determinado lugar para encender o apagar las luces al anochecer o amanece, además de evitar el gasto excesivo de energía
eléctrica, porque mantiene las luces encendidas sólo mientras falta luz natural, también ayuda a economizar la presencia de un operador humano para conectarlas o desconectarlas. 

2.4. MATERIAL Y EQUIPO REQUERIDO

Tabla de materiales

<img width="717" alt="tabla" src="https://user-images.githubusercontent.com/117534483/204937247-7de28e22-9317-4ee5-b432-e4b808f4d0bd.png">

Circuito esquematico a evaluar y armar

![C1](https://user-images.githubusercontent.com/117534483/204937399-7fbf0a57-be91-4788-972d-30e215ced05d.png)

Circuito armado en tinkercad.

<img width="870" alt="CT1" src="https://user-images.githubusercontent.com/117534483/204937897-c9135c95-0366-4843-9411-7731cf251876.png">

<img width="875" alt="CT2" src="https://user-images.githubusercontent.com/117534483/204937899-b4e2cdfa-b783-41a0-a7b3-1168cd693b52.png">

2.5 Procedimiento

Usaremos un transistor bipolar np n2 n3 1904 vamos a polarizar lo negativo en su pin emisor en el colector conectaremos dos diodos led con una conexión en serie hasta llegar al positivo mediante una resistencia que al final lo colocaremos vamos a desactivar constantemente el transistor por su base usando una fotocelda conectada hacia negativo recordando que este transistor solo se activa por señal positiva podemos enviar una señal positiva para el transistor mediante un potenciómetro y una resistencia aquí usaremos la línea azul como positivo principal y la línea roja como positivo para los leds conectamos la resistencia y el potenciómetro en serie hasta llegar a la base del transistor desde el pin medio del potenciómetro la razón por usar una resistencia fija es para enviar señal positiva cuando el potenciómetro esté en valor cero provocando una división de voltaje estable ahora si conectamos la resistencia a los
lakes desde esta línea esta conexión solo la hice por comodidad alimentaremos del circuito desde los 6 voltios la fotos celda a recibir luz mantendrá apagado al transistor pero al momento de obstruir la luz su valor subirá permitiendo pasar la señal positiva de las resistencias al transistor activando los leds el potencial no te permite dejar pasar más señal positiva desbalanceando la división de voltaje y así activando más al transistor algo así como cambiar la sensibilidad del sensor y es así que se obtiene un sencillísimo detector de oscuridad con lex y un simple transistor.

Procedimiento grafico

VIDEO

https://youtu.be/rZlI7Ur1jpM

CONCLUSIONES



BIBLIOGRAFÍA

Androbot TECH. (2020, 16 noviembre). TOP 5 Proyectos Electrónicos con Transistores [Vídeo]. YouTube. https://www.youtube.com/watch?v=_xvCoOR89o4


