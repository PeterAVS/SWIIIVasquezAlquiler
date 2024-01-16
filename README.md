# SWIIIVasquezAlquiler
#Subdominios 
#Subdominios Principales:Gestion de alquileres, gestion de vehiculos
#Subdominios de apoyo: Gestion de Clientes   
#Subdominios genéricos: gestio pagos, Seguridad

#Cooperación 
#Gestión de Alquileres y Seguridad permite que ambos bounded contexts trabajen para garantizar alquileres de vehículos seguros para los clientes.

#Conformista
#El bounded context de Gestión de Pagos implementa las políticas de seguridad definidas en Seguridad mediante Conformist para garantizar transacciones seguras

#Cliente-Proveedor
#Gestión de Alquileres requiere conocer disponibilidad de vehículos para asignarlos a las solicitudes de los clientes

# Shared kernel
gestion de alquiler y gestion del cliente ambos bounded contexts comparten los datos de los clientes que realizan los alquileres.
