# Proyecto
Implementación de comprobantes de pago impresos. Proyecto piloto para la implementación de metodologías ágiles.

# Contexto
Se requiere adecuar el software TimedSoft para que sea posible visualizar las cuentas pendientes de pago de un paciente y poder capturar la información de un pago recibido, así  como emitir combprobantes de pago impresos (Tickets) donde contenga información del pago, y saldo pendiente. 

# Objetivos
* Registrar en base de datos los pagos de los clientes. 
* Aumentar el control sobre los ingresos de la caja.
*	Eliminar la elaboración de recibos manuales. Se realiza con papel y pluma.
*	Elaboración de resumen de pagos y recibos impresos diarios. El corte se hace manual.
*	Aumentar la satisfacción del cliente al brindar información detallada de la compra.		

# Metas:
		Desarrollar módulo para administración de pagos.
		Foliado y almacenamiento de los recibos en base de datos.
		Elaboración de resumen de pagos y recibos impresos diarios. 
		Módulo de ajustes al recibo.

# Fases:
		- Obtención de información para mostrar en pantalla: Artículos, precios, configuraciones.
		- Visualización de artículos pendientes de pagos.
		- Generación de pagos.		
		- Generación de recibos donde no hay descuentos ni pagos.
		- Generación de recibos donde hay descuentos, pero no hay pagos
		- Generación de recibos donde hay descuentos y abonos pero no pagos completos
		- Generación de recibos donde hay descuentos, abonos y pagos.
		- Cancelación de pagos.
		- Generación de corte diario (pagos y recibos impresos)
		- Desarrollo de módulo para modificar las configuraciones de los comprobantes y pagos.

# Prácticas ágiles
- Entregamos software funcional frecuentemente.
Anteriormente nos esperabamos hasta el final del proyecto para hacer una sola entrega. Ahora hemos llevado este software de poco a poco, haciendo retroalimentación con el usuario final. Por ejemplo, ahorita pueden imprimir los comprobantes, pero no pueden cancelar, ni configurar el iva.
  
- Aceptamos que los requisitos cambien inclusive en etapas tardías del desarrollo.

- La simplicidad es escencial. NO usar cosas por si las dudas. 
Podremos agregar muchas cosas más impresas como: Indicaciones para el paciente, usuario de acceso, pero lo hemos dejado para otra etapa para enfocarnos en 
el backlog principal

- Se implementaron las historias de usuario, hacen claros los objetivos y nos enfocamos.

- La retroalimentación diaria de las cosas que logramos y nos detuvieron fueron escenciales para dar marcha rápida al proyecto.
