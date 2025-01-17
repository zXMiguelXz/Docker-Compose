# DOCKER COMPOSE DE ELK
**ANTES DE EJECUTAR LEA LA INFORMACIÓN** 

Para ejecutar ponga:
```
docker-compose up -d 
```

# Información Importante
Configurar el archivo .env ya que:

- La versión de elastic es la *8.9.2*, aunque esta versión la puedes cambiar en el archivo .env.

- El puerto de elastic es *9200*  el de kibana es *5601* aunque dichos puertos pueden modificar en el .env.

Debes de cambiar la contraseña que hayas configurado en el archivo .env y ponerla en el archivo logstash.conf

El puerto de logstash es el 5044.

# Requisitos Mínimos
- CPU: 2 núcleos
- Memoria: 4GB
- Almacenamiento: 10 GB

# Requisitos Recomendados
- CPU: 4-8 núcleos
- Memoria: 8GB
- Almacenamiento: 20 GB

# Versiones
- Sistemas operativos
   -
   - Ubuntu 22.04+
   - CentOS 8+
   - Debian 11+
- Docker y Docker Compose
   - 
   - Docker version: 20.10+
   - Docker Compose version: 1.29+ 