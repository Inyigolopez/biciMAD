
# BASES BICIMAD

Datos de las bases del servicio público de bicicleta eléctrica de la ciudad de Madrid.


Ultima actualización de los datos: 27/08/2018


* **Número**: Número de identificación de la estación
* **Gis_X**: Longitud en el sistema de coordenadas EPSG23030 (UTM 30N)
* **Gis_Y**: Latitud en el sistema de coordenadas EPSG23030 (UTM 30N)
* **Fecha de Alta**: Fecha de alta de la estación
* **Distrito**: Distrito de Madrid en el que se situa
* **Barrio**: Barrio de Madrid en el que se sitúa
* **Calle**: Calle en la que se sitúa
* **Nº Finca**: Número de calle
* **Tipo de Reserva**: Tipo de reserva al que pertenece
* **Número de Plazas**: Numero máximo de puestos de carga y aparcamiento de la estación
* **LONGITUD**: Longitud en el sistema de coordenadas EPSG4326 (WGS84)
* **LATITUD**: Latitud en el sistema de coordenadas EPSG4326 (WGS84)
* **DIRECCION**: Dirección completa


# BIKE DATA

Datos de uso de septiembre de 2018

* **id**: id del trayecto
* **user_day_code**: Código del usuario. Para una misma fecha, todos los movimientos de un  mismo  usuario,  tendrán  el  mismo  código,  con  el  fin  de  poder  realizar  estudios estadísticos de las tendencias diarias de los usuarios.
* **idunplug_station**: Número de la estación de la que se desengancha la bicicleta. 
*  **idunplug_base**: Número de la base de la que se desengancha la bicicleta. 
* **idplug_station**: Número de la estación en la que se engancha la bicicleta. 
* **idplug_base**: Número de la base en la que se engancha la bicicleta.
* **unplug_hourTime**: Franja horaria en la que se realiza el desenganche de la bicicleta. Por  cuestiones  de  anonimato,  se  facilita  la  hora  de  inicio del  movimiento,  sin  la información  de  minutos  y  segundos.  Todos  los  movimientos  iniciados  durante  la misma hora, tendrán el mismo dato de inicio. 
* **travel_time**:  Tiempo  total  en  segundos,  entre  el  desenganche  y  el  enganche  de  la bicicleta.
* **user_type**: Número que indica el tipo de usuario que ha realizado el movimiento. Sus posibles valores son: 
    - 0: No se ha podido determinar el tipo de usuario 
    - 1: Usuario anual (poseedor de un pase anual) 
    - 2: Usuario ocasional 
    - 3: Trabajador de la empresa
* **ageRange**:  Número  que  indica  el  rango  de  edad  del  usuario  que  ha  realizado  el movimiento. Sus posibles valores son: 
    - 0: No se ha podido determinar el rango de edad del usuario 
    - 1: El usuario tiene entre 0 y 16 años 
    - 2: El usuario tiene entre 17 y 18 años 
    - 3: El usuario tiene entre 19 y 26 años 
    - 4: El usuario tiene entre 27 y 40 años 
    - 5: El usuario tiene entre 41 y 65 años 
    - 6: El usuario tiene 66 años o más
* **zip_code**: Texto que indica el código postal del usuario que ha realizado el movimiento.  