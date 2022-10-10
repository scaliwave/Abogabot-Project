# Descripcion del Caso

Un despacho de abogados requiere un sitio web en el que se automatice la creacion de demandas por parte de sus clientes solicitantes, esto se hace a traves de un formulario en el cual se toman los datos de la solicitud. Una vez finalizada la solicitud, se procede con el pago. Efectuado este, se procede con la revision por parte del despacho para generar el documento legal correspondiente a la demanda.
______________________________________________________________________________________________________________________________________________________________________

## Analisis de Requerimientos

- El sitio web debe contener un registro tanto para administradores (despacho de abogados) como para solicitantes (personas demandantes)

- El sitio web debe notificar tanto al solicitante como al administrador durante todo el proceso de la creación de la demanda

- El sitio web debe permitir al administrador crear comentarios a cerca de la demanda (preferiblemente crear un sistema de chat para la comunicación cliente – abogado)

- El sitio web debe generar en formato Word la solicitud del demandante siemore y cuabdo se haya efectuado el pago y se hayan corregido las observaciones por parte del abogado

- El administrador debe tener un dashboard con todos los pagos efectuados

- La aplicación web debe ser responsive para verla desde el celular o PC

- Les gustaría incluir colores azul marino y blanco, pero aceptan sugerencias

_______________________________________________________________________________________________________________________________________________________________________

## Diagrama de flujo del negocio

> ***En esta parte va el diagrama BPMN o de actividades indicando el flujo del negocio***
_______________________________________________________________________________________________________________________________________________________________________

### Explicacion del flujo

Inicialmente se tiene una pagina de inicio o login de usuarios, si el usuario desea registrarse, se redirige a una nueva página con un formulario de registro.

Para el regitro se debe tener en cuenta tres roles: 
1. **Rol de solicitante** --> Persona particular que crea la demanda.
2. **Rol de Abogado**     --> Abogado del despacho con opciones unicas dentro del sitio web.
3. **Rol Administrador**  --> Persona encargada de adminsitrar el sitio con derechos especiales.


