# Zabbix-Sonicwall
Plantilla Zabbix y dispositivos, Sonicwall, Gen 6.5 y Gen 7
Plantilla de Zabbix para la parametrización de dispositivos Sonicwall, por SNMP y API.
Plantilla, exportada de un Zabbix v6 Beta3.
Probada en SonicOS 5.9xx, 6.2xx, 6.5xx y 7.0.1 Modelos SOHO, SOHO250 TZ series (300, 350, 370, 400,470, 500, 600, 670) NSA series, (2600, 2650, 2700.) y en modelos NSA 3600 y 4600 Pero poco tiempo.
Mejoras frente a otras plantillas disponibles:
Identificación del USO del ControlPlane vs DataPlane. (Core0 y el resto de cores.)
Identificación de SonicPoints y multiples datos a tener en cuenta (Incluidos los Wave)
Consulta de API, en SonicOS que lo soporta, aportando datos relevantes como licencias, y uso de las mismas.(en relación a la cuantía de ellas, uso para SSLVP y GVPN)
Muchas otras características aportadas.
