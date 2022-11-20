# Descripción del Caso

Un despacho de abogados requiere un sitio web en el que se automatice la creacion de demandas por parte de sus clientes solicitantes, esto se hace a traves de un formulario en el cual se toman los datos de la solicitud. Una vez finalizada la solicitud, se procede con el pago. Efectuado este, se procede con la revision por parte del despacho para generar el documento legal correspondiente a la demanda.
______________________________________________________________________________________________________________________________________________________________________

## Requerimientos

- El sitio web debe contener un registro tanto para administradores (despacho de abogados) como para solicitantes (personas demandantes)

- El sitio web debe notificar tanto al solicitante como al administrador durante todo el proceso de la creación de la demanda

- El sitio web debe permitir al administrador crear comentarios a cerca de la demanda (preferiblemente crear un sistema de chat para la comunicación cliente – abogado)

- El sitio web debe generar en formato Word la solicitud del demandante siemore y cuabdo se haya efectuado el pago y se hayan corregido las observaciones por parte del abogado

- El administrador debe tener un dashboard con todos los pagos efectuados

- La aplicación web debe ser responsive para verla desde el celular o PC

- Les gustaría incluir colores azul marino y blanco, pero aceptan sugerencias
_______________________________________________________________________________________________________________________________________________________________________

## Toma de requerimientos

En el siguiente link tendrás acceso al <a href= https://github.com/scaliwave/Abogabot-Project/blob/main/1.-Requerimientos.doc>levantamento de requerimientos</a>

_______________________________________________________________________________________________________________________________________________________________________

## Buyer persona

En en el siguiente link encontrarás el <a href = https://github.com/scaliwave/Abogabot-Project/blob/main/2.-%20Buyer%20Persona.pdf> Buyer persona</a>

_______________________________________________________________________________________________________________________________________________________________________

## Publico Objetivo


_______________________________________________________________________________________________________________________________________________________________________

## Diagrama de flujo del negocio


![diagram](https://user-images.githubusercontent.com/89940115/199050300-e7aa699a-695d-4777-88f8-b340e362d362.png)

_______________________________________________________________________________________________________________________________________________________________________

### Explicación del flujo

***Inicialmente se tiene una página de inicio o login de usuarios, si el usuario desea registrarse, se redirige a una nueva página con un formulario de registro.***

Para el ***regitro*** se tendran en cuenta tres roles:
1. **Rol de solicitante** → Persona particular que crea la demanda.
2. **Rol de Abogado**     → Abogado del despacho con opciones unicas dentro del sitio web.
3. **Rol Administrador**  → Persona encargada de adminsitrar el sitio con derechos especiales.

Se manejarán los roles de acuerdo al correo registrado por parte de los usuarios

***Una vez adentro, existirá una interfaz para cada tipo de usuario, detallada a continuación:***
### Solicitante
- Contará con un perfil donde podrá realizar cualquier tipo de cambio de datos personales.
- Contará con una Opción para crear Nueva Demanda
- Podrá Consultar el Estado de la Demanda con los comentarios referentes al proceso.
- Tendrá un Chat para comunicarse con el abogado asesor
- Tendrá una opcion para descargar su demanda en formato WORD una vez se haya dado la aceptación del abogado
- Contara con una opción para corregir los datos de su demanda
- Deberá contar con una formato para realizar pagos en línea.
### Abogado
- Contará con un perfil donde podrá realizar cualquier tipo de cambio de datos personales.
- Tendrá un sistema de notificación de Nueva Demanda donde se mostrará el nombre de la solicitud del cliente
- Tendrá la posibilidad de actualizar el estado de la demanda y comentar los cambios necesarios para completarla 
- Contará con un chat para mensajes con el cliente
- Contará con un dashboard para ver el total de sus demandas con sus pagos 
- Una vez aprobada la demanda, el sitio web debe permitir generar de forma automática el documento legal en formato Word para que el cliente la descargue.
### Administrador
- Contará con un perfil de usuario.
- Tendrá permisos especiales como eliminar abogados del despacho, actualizar el formato de creación de demanda, etc.


  


