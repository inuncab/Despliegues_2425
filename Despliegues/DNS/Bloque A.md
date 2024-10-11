## DNS (Domain Name System)
El **DNS** es una tecnología que permite resolver nombres en redes, traduciendo nombres de dominio en direcciones IP para acceder a sitios web.

## Resolución de dominio
Proceso de traducir dominios legibles por humanos a direcciones IP, facilitando la navegación por Internet.

## Dominios y subdominios
Un **dominio** es un nombre que identifica un sitio en Internet. Un **subdominio** es una extensión del dominio principal, apuntando a una sección específica del sitio.

## Búsqueda de dominio DNS
Divisiones del espacio de nombres DNS llamadas **zonas de búsqueda** contienen información sobre dominios. Estas zonas permiten organizar y gestionar los nombres de dominio eficientemente.

## Tipos de servidores DNS
- **Servidor recursivo**: Recibe consultas y puede usar caché o reenviar la consulta.
- **Servidor autoritativo**: Contiene información oficial sobre dominios.
- **Servidor raíz**: Redirige consultas a servidores autoritativos para dominios superiores.
- **Resolutor**: Realiza consultas DNS en los dispositivos.

## Registros DNS
Archivos de mapeo que indican a los servidores la IP correspondiente a un dominio. Tipos:
- **A**: Dirección IP.
- **MX**: Servidores de correo.
- **NS**: Servidores autoritativos.
- **CNAME**: Aliases de dominios.
- **PTR**: Mapeo inverso.
- **SOA**: Información administrativa.

## Consulta recursiva
Proceso en el cual un servidor DNS recursivo busca información sobre un dominio:
1. Verifica caché local.
2. Consulta servidores raíz.
3. Envía la consulta al servidor autoritativo.
4. Devuelve la respuesta.

## Consulta iterativa
Método que distribuye la búsqueda de información entre varios servidores:
1. Empieza en servidores raíz.
2. Pasa a servidores autorizados.
3. Termina en servidores del dominio objetivo.

### Beneficios:
- Mejora rendimiento y escalabilidad.
- Tolerancia a fallos al permitir consultas alternativas.
