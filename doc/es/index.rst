=================================================
Número de dígitos en códigos de cuentas contables
=================================================

Este módulo permite especificar el número de dígitos de los códigos de las
cuentas contables, tanto la creación como la actualización de cuentas contables.

Antes de ejecutar el asistente de creación de cuentas contables en Tryton, deberá
añadir el número de dígitos en la configuración de contabilidad. Si instala el módulo
a la vez que **account_es** deberá cancelar el asistente de creación de cuentas
contables y ejecutarlo manualmente después.

El número de ceros a expandir en el código de las cuentas contables dependerá
de la plantilla de cuentas contables. A modo de ejemplo, para un plan contable
de ocho dígitos:

* Si ponemos el código *4300* nos añadirá cuatro ceros al final: 43000000
* Si ponemos el código *4300%1* nos remplazará el *%* por ceros hasta completar
  los ocho dígitos: 43000001
