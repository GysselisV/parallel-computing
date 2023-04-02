### 1. En entornos compartidos, los usuarios comparten el sistema. Esto puede dar lugar a varios problemas de seguridad. 

*a)* Mencione dos problemas y explíquelos. 

***Brechas de privacidad/seguridad***: Esto se da cuando usuarios con malas intenciones obtienen acceso a información confidencial de otros usuarios, es decir que podrían ver datos como correos electrónicos, documentos, números de contacto y demás datos personales que no deberían ser visibles para cualquiera. (Samaniego, 2021).

Con esta vulnerabilidad se puede dar paso a un segundo problema que corresponde a la ***fuga de información***, y es que, con el acceso de cualquier usuario a esos datos, se puede compartir información confidencial, como nombres de usuario, contraseñas, etc. Y esta información puede ser robada y utilizada para fines ilegales, como es el caso del robo de identidad, acceso no autorizado a redes sociales e incluso a cuentas bancarias. (Santander, s.f.)




*b)* Es posible asegurar el mismo grado de seguridad en un sistema compartido que en un sistema dedicado. Explique su respuesta.

Es más complejo alcanzar el mismo grado de seguridad en un sistema compartido que en uno dedicado. La razón es que, en un sistema dedicado, la seguridad está enfocada únicamente en el sistema en sí y en los usuarios que están autorizados -que regularmente son pocos-, es por ello por lo que hay menos peligros y existe una menor probabilidad de que ocurran vulnerabilidades (Rodriguez, 2021). Por otro lado, en un sistema compartido, el enfoque es un poco más amplio, ya que los usuarios tienen acceso a los mismos recursos y a la misma estructura, y, en consecuencia, existe una mayor probabilidad de que ocurran vacíos de seguridad.

Ahora bien, lo anterior no quiere decir que resulte imposible lograr un alto grado de seguridad en un sistema compartido. Para garantizar que esto ocurra, se puede limitar el acceso, encriptar los datos, tener un sistema de autenticación de usuarios y realizar monitoreos constantemente (Intelligencia, 2017). Finalmente, es bastante importante que de manera conjunta se concientice a los usuarios sobre las buenas prácticas de seguridad informática. 

### 2.	Un problema común en los OS es la utilización de recursos. Enumere los recursos que deben gestionarse en las siguientes maquina (explique porqué):

***Sistemas embebidos***: memoria, procesador, energía, almacenamiento y dispositivos de entrada/salida.

Generalmente estos sistemas tienen recursos limitados y, regularmente, son utilizados en aplicaciones críticas en las que la disponibilidad, la fiabilidad y la eficiencia son esenciales. Deben ser gestionados cuidadosamente debido a las limitaciones de espacio y energía.

***Mainframe***: CPU, memoria, almacenamiento, red y seguridad.

En los mainframes, la gestión de recursos es fundamental debido a que varias personas los usan simultáneamente (IBM, s.f.), lo que puede afectar su eficiencia. Además, los mainframes se utilizan comúnmente para procesar información financiera y almacenar datos de clientes, por lo que la seguridad también es esencial.

***Workstation***: procesador, memoria, almacenamiento, tarjeta gráfica, dispositivos periféricos y seguridad.

Las workstations son comúnmente empleadas en campos como ingeniería, arquitectura, animación, diseño gráfico y edición de video, por lo que necesitan características técnicas superiores a las de una computadora de escritorio común, con procesadores más poderosos, más memoria RAM, tarjetas gráficas especializadas, monitores de alta resolución y almacenamiento veloz. (LAGE, 2019).

***Servidor***: CPU, memoria, almacenamiento, red, seguridad y balanceo de carga.

Los servidores se utilizan para alojar servicios y aplicaciones en línea, por lo que es esencial administrar la memoria, el almacenamiento y la red para procesar las solicitudes de los clientes y almacenar grandes cantidades de datos. Además, se debe implementar medidas de seguridad sólidas para proteger la información sensible y crítica almacenada en el servidor.

***Mobile***: CPU, memoria, almacenamiento, batería, conectividad y seguridad.

Los dispositivos móviles deben gestionar correctamente sus recursos para asegurar una buena duración de la batería y un rendimiento óptimo. Es importante administrar la memoria RAM para permitir la ejecución de múltiples aplicaciones y mejorar el rendimiento, el almacenamiento interno para almacenar archivos relevantes, la conectividad para mantenerse en línea y transferir datos, y la seguridad para proteger la privacidad del usuario y prevenir accesos no autorizados.

### 3.	Caracterice dos casos de uso para implementar un OS para servidor y PC.

El primer caso de uso se sitúa en una escuela que requiere un sistema operativo para sus servidores y computadoras personales que sea fácil de administrar. En cuanto al servidor, en este se requiere herramientas de colaboración y gestión de recursos para múltiples usuarios, mientras que en las computadoras personales se necesita software educativo.

El segundo caso de uso se refiere a una empresa de comercio electrónico que necesita un sistema operativo para servidor y PC para alojar su sitio web de venta en línea y gestionar eficientemente todos los movimientos. Por parte del sistema operativo del servidor, este debe ser seguro, garantizar la privacidad y seguridad de los datos de los clientes. Por otro lado, para las computadoras personales se necesita un sistema operativo que ofrezca herramientas de gestión de ventas para los empleados de la empresa, con una interfaz de usuario intuitiva y que permita el control de inventario y seguimiento de transacciones.

### 4.	Compare las diferencias entre multiprocesamiento simétrico y asimétrico

<table>
  <tr>
    <th>Simétrico</th>
    <th>Asimétrico </th>
  </tr>
  <tr>
    <td>Los procesadores tienen la misma capacidad de procesamiento y pueden realizar las mismas tareas con la misma eficiencia</td>
    <td>Un procesador puede estar diseñado para realizar una tarea específica de manera más eficiente que el resto.</td>
  </tr>
  <tr>
    <td>procesadores idénticos comparten el mismo espacio de memoria</td>
    <td>Procesadores pueden tener diferentes niveles de acceso a recursos compartidos como memoria</td>
  </tr>
  <tr>
    <td>Mayor escalabilidad</td>
    <td>Escalabilidad limita</td>
  </tr>
  <tr>
    <td>la carga de trabajo se distribuye de manera uniforme</td>
    <td>La carga de trabajo se asigna de manera desigual según las habilidades y capacidades de cada procesador</td>
  </tr>
  <tr>
    <td>Todos los procesadores ejecutan tareas sobre el SO</td>
    <td>Solo el procesador maestro ejecuta tareas sobre el SO</td>
  </tr>
</table>


### 5.	Enumere los requerimientos para que dos máquinas se junten en un clúster y provean un servicio de alta disponibilidad (HA).

Para que dos o más máquinas se unan en un clúster y proporcionen un servicio de alta disponibilidad, es necesario: 

1.	Una red de alta velocidad y confiable para comunicación y sincronización de datos entre las máquinas.
2.	Que las máquinas que integran el clúster cuenten con hardware compatible en arquitectura de CPU, capacidad de memoria y almacenamiento.
3.	Instalar un software de clúster que permita a las máquinas trabajar en conjunto.
4.	La sincronización de datos para asegurarse de que todas las máquinas del clúster tengan la misma información y configuración.
5.	herramientas de monitoreo y administración para detección de fallos.
6.	Para garantizar la continuidad del servicio en caso de fallas, es recomendable contar con componentes extra que puedan reemplazar a los componentes defectuosos.
