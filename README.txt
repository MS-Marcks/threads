Flood es una herramienta que consiste en enviar muchos paquetes SYN a un objetivo específico.
Un ataque de Denegación de Servicio Distribuido (DDoS) es un intento de hacer que un servicio 
en línea no esté disponible abrumándolo con tráfico de múltiples fuentes.
un servicio en línea abrumándolo con tráfico de múltiples fuentes.

instalación:
1.escriba make
2.ejecute el archivo flood con el usuario Admin/root

sintaxis: ./flood [-t IP] [-p PORT] [-r]

opciones:
	-t (IP del objetivo): IP (defecto 127.0.0.1)
	-p (PUERTO del objetivo): PORT (defecto 80)
	-r establecer RST flag

	Ejemplo: sudo ./flood -t 192.168.0.1 -p 8080"
