#Ejercicio 1

He encontrado el modelo Lenovo 5464E3G en la tienda online de Senetic España. Su coste en dicha tienda es de 1824,31 euros.

Vamos a calcular su coste de amotización en base al artículo proporcionado: [Cómo calcular el coste de amortización de un ordenador portátil](http://www.infoautonomos.com/consultas-a-la-comunidad/988/)

Comencemos. Partimos de considerar un IVA del 21% y suponemos que lo hemos comprado a principios de año, en enero por ejemplo. Siendo así tenemos:

##Amortización a 4 años

Le quitamos el IVA para calcular su primer año, eso nos deja el precio del ordenador al final del primer año en (aproximadamente): 1824-(1824*0.21)= 1440 euros. Una vez hecho esto sólo tenemos que dividir entre el número de años restantes para calcular la amortización por año: 1440/3=480 euros. Es decir:

-Primer año: 384 euros
-Segundo año: 480 euros
-Tercer año: 480 euros
-Cuarto año: 480 euros

##Amortización a 7 años
Partiendo del mismo IVA, ahora en vez de dividir entre 3 dividimos entre 6. Esto nos da un coste de amortización de 384 euros el primer año y de 240 euros cada año.


#Ejercicio 2

Voy a comprar dos servicios de hosting en internet con características bastante similiares. En ambos he escogido el plan más básico que ofrecen y vamos a comparar precio y características entre ellos:

##Hostalia
El coste de este servicio es de 99.60 euros al mes (69.90 euros el primer mes) y nos ofrece un modelo Dell PowerEdge R200 con un procesador con 4 cores de 3.5 GH, 16 GB de memoria RAM y dos discos duros SATA de 1 TB.

Podemos ver mas información en: [Planes hostalia](https://www.hostalia.com/dedicados/?utm_medium=cpc&utm_source=google&utm_content=busqueda&utm_campaign=google_servidoresdedicados_hosting_exacto&gclid=CjwKEAjws7OwBRCn2Ome5tPP8gESJAAfopWsTkhaReicx0JHaLjrgbbldKDaRJBKBp8tmU_b-rJ6GxoCOWTw_wcB)
##Azure
Como proveedor de servicios en la nube he escogido Azure. En la opción de contratar una máquina virtual he escogido una que se asemeja a la alternativa que nos ofrece Hostalia y lo más parecido que he encontrado es: una máquina virtual con un procesador de 4 cores, 14 GB de memoria RAM y 200GB de disco. Lo único que difiere bastante es el tamaño del disco duro, pero este es el plan que más se aproxima al anterior; corresponde a la instancia D3 que podemos encontrar pinchando en el enlace: [Planes Azure](https://azure.microsoft.com/es-es/pricing/details/virtual-machines/)

El precio de este plan es de 0.5364 euros/h, es decir aproximadamente 399 euros al mes.
##Cálculo
Una vez tenemos las dos opciones sobre la mesa vamos a calcular el coste al año de ambas si:

- **La infraestructura se usa el 1% del tiempo:**
	
	- En el caso de Hostalia nos sale un coste al año (descartando la rebaja del primer mes ya que a largo plazo se vuelve minúscula) de 99.6*12=1195.2 euros. Como podemos ver el gasto es el mismo independientemente del tiempo que usemos el servicio.

	- En el caso de Azure, para calcular su coste al año hacemos: 399 €/mes * 12 meses * 0.01= 47.88 €/año

Como podemos observar, si lo usamos solo el 1% del tiempo sale mucho más rentable contratar un servicio por uso.

- **La infraestructura se usa el 10% del tiempo:**

	- En el caso de Hostalia nos sale un coste al año (descartando la rebaja del primer mes ya que a largo plazo se vuelve minúscula) de 99.6*12=1195.2 euros.
	- En el caso de Azure, para calcular su coste al año hacemos: 399 €/mes * 12 meses * 0.1= 478.8 €/año

Si la utilización es del 10% sigue siendo más rentable contratar un servicio por uso frente a un alojamiento por acceso.

##Extra: ¿en nuestro caso, cuando empieza a ser rentable la primera opción?
Sin más que resolver 399 * 12 * x = 1195.2 =====> x=0.2496

Es decir, si la utilización es de más del 24.96% es más rentable la primera opción. Esto nos dice que para aplicaciones de prueba, por ejemplo, es mucho más conveniente un plan con Azure, que tener que contratar un servicio de alojamiento por acceso.
	