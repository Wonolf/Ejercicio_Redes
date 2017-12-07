# Ejercicio_Redes

Ejercicio Realizado con Cisco Packet Tracer 6.2.0

-Crear 5 redes:

    1.  Crear tres subredes (VLSM), una que soporte 100 host, otra que soporte 30 
        y por último una para 6 host. Sólo esta última podrá salir fuera. 
        Cada una tendrá cuatro ordenadores conectados.
        Cada red de 4 ordenadores tendrá un grupo de IP fija. Las 3 subredes estarán
        conectadas a un mismo switch.
				
    2.  8 ordenadores con DHCP.
        Todos los ordenadores deberán estar conectados a un servidor mediante un switch.
        Este servidor proporcionará las IP de cada ordenador mediante la configuración DHCP.
        
    3.  4 ordenadores con DHCP.
        De igual forma que en el caso anterior, los ordenadores deben estar conectados a
        un servidor mediante un switch. Este servidor proporciona las IP a los ordenadores
        por configuración DHCP.
        
    4.  4 ordenadores con IP fija, un punto de acceso con 5 ordenadores con DHCP.
        Los cuatro ordenadores con IP Fija estarán conectados a un mismo switch. 
        Para los ordenadores con DHCP, hará falta un servidor con la configuración IP
        y un punto de acceso que conecte a cada ordenador DHCP. Para ello, establecemos
        un nombre de red y una contraseña, en este caso WPA2-PSK. Tanto el servidor como
        el punto de acceso deben estar conectados al mismo switch que los 4 ordenadores
        con IP Fija.
        
    5.  5 ordenadores con IP fija.
        Conectamos 5 ordenadores con IP Fija a un mismo switch.
        
- Todas las redes estarán conectadas mediante routers.

    Cada red debe estar conectada a un router, y los 5 routers distintos deben de estar
    conectados en línea. En este caso he utilizado routers de clase 1841.
    
- Tendremos tres servidores web:    

    1. www.albacete.es
    2. www.wagner.de
    3. www.dilar.com
    
    He montado estos servidores en la red 5. Un servidor principal contiene la información
    de las páginas web, y cada uno de los 3 servidores se encarga de mostrar la 
    información correspondiente.
