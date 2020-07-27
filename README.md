# IOTAgro
App Mobile &amp; Web Platform
# Sistemas de supervisión, control y gestión de procesos en terreno - Predios Agrícolas
El desarrollo consiste en una idea para la supervisión, control y gestión que
realizan los Supervisores a cada uno de los Predios que existe en un acuerdo de
Cultivo Agricola.

# ALCANCE:
 Los principales objetivos son:
- Registro de cada uno de los Predios de Cultivo (Terreno, Dueño, Características, etc.) y el
registro de las Visitas que cada Supervisor realiza al Predio periódicamente (Visita,
Agendamiento, Recomendaciones, Fotografías, Localización, Historia, Recomendaciones de
compras, etc.)
- Control y gestión para los Supervisores y el Equipo directivo de la empresa Agrícola para el seguimiento del
Cultivo en cada Predio y del trabajo realizado
- Medición de las variables agronómicas claves en cada Predio (10 Estacas de medición) y
registro en el Sistema para cada una de las Visitas del Supervisor
- Comunicación al Agricultor de la visita a realizar y del resultado de la visita incluyendo las
recomendaciones (SMS y Correo)
- Trazabilidad de las actividades en cada Predio para las solicitudes de Clientes de la empresa Agricola.

# REQUERIMIENTOS FUNCIONALES:
-	Login en sistema mediante credenciales de acceso precargados.
-	Obtener datos precargados de predio.
-	Generar un mantenedor (ingresar, modificar y eliminar) para cada ítem del sistema.
-	Almacenar en dispositivo móvil la información de cada visita, hasta obtener conexión internet que permita subirla a la nube. 
-	Obtener geo posicionamiento automático.
-	Generar SMS con datos acotados de cada visita realizada por el técnico a cargo, a los dueños del predio.
-	La plataforma Mobile funcionara, tanto online como offline.
-	La plataforma Mobile tiene las opciones de sincronización por técnico, mediante su RUT.
-	La plataforma Web consta de generadores de gráficas y métricas de información, con la posibilidad de realizar la exportación a Excel.
-	La plataforma Web se encuentra perfilada y con diferentes layout de acuerdo al usuario que ingresa al sistema.
-	Generar los siguientes informes a partir de los datos recabados por el sistema:
o	Reporte 1: Contratos en los cuales se ha registrado una última visita deficiente en el QA, ordenado por Técnico.
o	Reporte 2: Contratos sin visitar con más de 7 días, ordenados por Técnico.
o	Reporte 3: Número de visitas por Contrato a la fecha, ordenado por Visitas (Menor a Mayor) y el Técnico y las Ha.
o	Reporte 4: Planificación de cosecha por Contrato, indicando zona (Norte, Sur), rendimiento esperado, variedad y Técnico, (Aptitud de cosecha mecánica última visita). Contratos que están aptos para cosecha los próximos 15 días.
o	Reporte 5: Visitas por técnico en la semana, Contratos, Hectáreas
o	Reporte 6: Cuaderno de campo por contrato. Indica todas las labores recomendadas confirmadas

#	REQUERIMIENTOS NO FUNCIONALES:
Detalle de Requerimiento	y Descripción:
- Usabilidad:	Debe ser fácil de usar. Con ayudas e interfaces intuitivas.
- Seguridad:	El ingreso al sistema estará restringido bajo contraseñas y usuarios definidos
- Portabilidad:	El sistema debe brindar comodidad al usuario y a otras áreas. Es por ello que el entorno donde se muestre el sistema a los diferentes usuarios será personalizado acorde a su labor dentro del mismo, como, por ejemplo; a los usuarios en terreno se le brindara acceso al sistema a través de una Tablet, mientras que, a los usuarios oficinistas, será a través de entorno web, brindando acceso desde cualquier dispositivo con conexión a internet.
- Rendimiento:	El sistema será capaz de soportar el manejo de gran cantidad de información durante su proceso.
- Tolerante a Fallos:	El sistema será capaz de operar tanto online como offline en caso de no contar con acceso inmediato a internet, con el fin de subir información al momento de reestablecer conexión con la nube. 
- Escalabilidad:	El sistema será escalable, en caso de aumentar el número de usuarios o requerimientos a nivel de software y/o hardware.

# 9.	MODELO ENTIDAD RELACION:
