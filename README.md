# MSSQL Docker Failover Replication

Este proyecto implementa un entorno de replicación para Microsoft SQL Server utilizando Docker y failover manual. 

Incluye dos instancias de SQL Server (primaria y secundaria) que comparten un volumen para replicar logs mediante log shipping. En caso de fallo de la instancia primaria, un script personalizado permite activar la secundaria como nueva principal.

> 🔧 Proyecto en desarrollo — más detalles serán agregados conforme avance la implementación.
