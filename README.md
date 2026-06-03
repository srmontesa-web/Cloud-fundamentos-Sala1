# Ejercicio Cloud — [Sala1]
## 1. Nuestros datos- Grupo: [A]- Integrantes: [Gema, Ricardo, Javier]- Fecha: [3-junio-2026]
## 2. Nuestra infraestructura Liferay actual (on-premise)- Servidor de aplicaciones: [Liferay 7.3]- Base de datos: [Oracle]- Almacenamiento: [disco local]- Copias de seguridad: [total y diarias]
## 3. Tabla de responsabilidades: quién hace qué
> Marcad con **X** quién es responsable en cada modelo.
| Tarea | On-Premise | IaaS | PaaS | SaaS |
|---|---|---|---|---|
| Instalar el sistema operativo del servidor | Nosotros | Nosotros | Proveedor | Proveedor |
| Aplicar parches de seguridad del SO        | Nosotros | Nosotros | Proveedor | Proveedor |
| Actualizar Liferay a nueva version         | Nosotros | Nosotros | Nosotros  | Proveedor|
| Gestionar backups de la base de datos      | Nosotros | Nosotros | Nosotros  | Proveedor|
| Renovar certificados SSL (HTTPS)           | Nosotros | Nosotros | Proveedor | Proveedor|
| Escalar el servidor en picos de trafico    | Nosotros | Nosotros | Proveedor | Proveedor|
| Monitorizar CPU y memoria del servidor     | Nosotros | Nosotros | Proveedor | Proveedor|
| Configurar el firewall y la red            | Nosotros | Nosotros | Proveedor | Proveedor|
| Instalar y configurar el balanceador       | Nosotros | Nosotros | Proveedor | Proveedor|
| Gestionar el motor de busqueda (Elasticsearch) | Nosotros | Nosotros | Nosotros | Proveedor|
## 4. Nuestra recomendacion para ESTILA 
**Modelo elegido:** [PaaS]
**Por que:** [Liferay nos obliga a ir a Cloud pero la infraestructura de los datos será ON-PREMISE (infraestructura propia)]
**Tareas que dejaremos de gestionar nosotros:** [
Todo el hardware de Liferay, su almacenamiento propio y red (Configuración de firewall y balancedor).
Actualizacion de Sistema operativo, parches de seguridad y certificados.
Escalabilidad según demanda.
Monitorización de recursos de máquinas.
]
**Tareas que seguiremos gestionando nosotros:** [
Mantenimento de BBDD de la información on-premise (integridad, backups y seguridad).
Software de la BBDD on-premise (versiones, librerias y funcionalidad propia).
Software de Liferay (versiones, librerias y funcionalidad propia).
Configuración de Liferay.
Accesos con MFA en la aplicación de Liferay.
Configuración de roles de usuarios de aplicación de Liferay.
Información que puede ver el usuario en la aplicación de Liferay.
Tareas que puede hacer cada usuario en la aplicación de Liferay.
]
