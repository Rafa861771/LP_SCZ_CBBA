# LP_SCZ_CBBA
1.Paso 1 Diseño de red

Creé una red con tres routers, donde el principal es Router_Principal_Cbba, y los otros dos lpz y scz que están conectados a él.

Utilicé switches para conectar grupos de PCs en diferentes subredes.

Conecté los routers con enlaces seriales y los switches con cables Ethernet.

2. Asignación de Direcciones IP

Usé diferentes redes para cada segmento de la red:

20.2.0.0/24 para un grupo de PCs.

200.20.0.0/24 para otro grupo.

10.3.0.0/24, 160.20.0.0/24, 140.10.0.0/24, y 128.10.0.0/24 para interconectar routers.

3. Configuración de Routers

Asigné las IPs en cada interfaz GigabitEthernet 

Usé rutas estáticas para permitir la comunicación entre las redes.

4. Configuración de Switches y PCs

Configuré los switches con una IP de administración.

Asigné IPs a las PCs dentro de su respectiva subred y configuré sus puertas de enlace.

Resultado: La red quedó funcionando 
