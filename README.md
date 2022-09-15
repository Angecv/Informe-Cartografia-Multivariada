# ***Mapeo de los edificios en la Finca dos de la UCR sede Rodrigo Facio.*** 
 
## Resumen. 
  
Este trabajo pretende contribuir a que las personas que visitan la finca dos de la Universidad de Costa Rica, sede Rodrigo Facio, puedan orientarse mejor en la gran extensión territorial de esta finca y conocer algunas características fundamentales sobre la seguridad y confort que ofrecen los edificios, a través de la elaboración de un mapa temático que contenga esa información espacial, plasmada en un geo visualizador que se encuentre en línea. Y de esta forma, facilitar el acceso y la utilización de los datos recolectados dentro de la finca dos: Ciudad de la Investigación. 
 
## Introducción. 
 
La recolección de información y el análisis de datos presenta un gran auge; por su parte la geovisualización está teniendo una mayor importancia, ya que este permite combinar procesos de comunicación con variables espaciales. A su vez, esta ha ido creciendo con la cartografía que no solo busca representar la Tierra en un plano cartográfico, sino que tiene como fin de comunicar más allá de lo que se muestra. La geovisualización se define como un espacio físico delimitado que incorpora la exploración visual, el análisis, la síntesis, y la presentación geoespacial de datos, gracias a la integración de diferentes enfoques, que van desde la cartografía hasta el análisis de datos (Vidal, et al. 2011). 
 
Comúnmente, los datos espaciales poseen un componente temporal, por lo que se presentan como una estructura compleja, la cual incluye el espacio, el tiempo, y un número determinado de atributos temáticos, todo este conjunto permite plantear cambios en la visualización. Actualmente se cuenta con una variedad de herramientas tecnológicas que permiten una mayor profundización y comprensión de los fenómenos espaciales. Todos estos cambios que hoy en día se encuentran, corresponden a lo que se conoce como la “revolución multimedia”, que se usa en el contexto social y cultural (Vidal et al. 2011). 
 
Asimismo, la combinación de softwares y diferentes plataformas, permiten presentar el producto final de la mejor manera posible, el cual se puede ajustar según las necesidades del producto que se pretende visualizar. Se presentan herramientas más flexibles que permiten la integración de los datos geoespaciales y el diseño visual del objetivo inicial. Por ende, es importante que todo este conjunto cumpla con las demandas que requieren tales productos. Por lo anterior, en este trabajo se presentan resultados de la recolección de datos espaciales que corresponden a los edificios de la Ciudad de la Investigación, cuyo objetivo es el uso de las diferentes herramientas SIG, y el producto final de un mapa temático con información general de los edificios antes mencionados, a disposición de quienes lo requieran. 
 
## Materiales y Métodos. 
 
En este trabajo el área de estudio corresponde a la Finca dos, Ciudad de la Investigación, de la Universidad de Costa Rica, sede Rodrigo facio ubicada en San Pedro de Montes de Oca. Dicha sede está compuesta por tres fincas las cuales son además de la Finca dos, la Finca uno y la Finca tres, que corresponde a las instalaciones deportivas. 
 
El primer paso para el mapeo de los edificios fue el planeamiento y creación del formulario para los correspondientes edificios, este formulario fue creado en Excel y contiene los diferentes atributos que se consideran de interés a la hora de visitar el campus. Seguidamente se realizó una revisión de mapas y planos de los edificios ubicados en el área de estudio. Una vez localizados de manera general los edificios, en el software QGIS, se realizó una digitalización de estas ubicaciones. Esto por medio de una geometría de puntos y también se integró el formulario por medio de la tabla de atributos. De manera que cada punto que se crea corresponde a un edificio y este contiene en la tabla de atributos la información que debe ser completada. 
 
Posteriormente se realizó un trabajo de campo en el cual se visitaron los distintos edificios para comprobar la localización y recolectar los datos del formulario. El llenado de los formularios se realizó por medio de la aplicación QField (ver figura 1). 
 
**Figura 1.** Formulario en QField. 
 
 ![](https://user-images.githubusercontent.com/111781085/190348543-af6c2199-0d77-4f72-b95c-93b5864e0406.png)
 
Por la naturaleza de la información, en ocasiones esta debía ser solicitada al personal administrativo de los edificios correspondientes. En el caso de los edificios destinados a investigación, estos presentan un acceso más restringido para el público general, mientras que los destinados a educación tienen apertura pública. Una vez recolectados los datos, en QGIS se creó una simbología que corresponde al tipo de uso del edificio, ya sea; investigación, educación, etc. La creación del mapa web se llevó a cabo en QGIS con el complemento: Qgis2web. Este complemento permite exportar las capas de un entorno de trabajo de QGIS a una página web en donde se puede observar proveniente de SIG sin la necesidad de instalar ningún programa, solamente descargando la carpeta que contiene el mapa web. 
 
## Resultados. 
 
Al representar los edificios de la finca dos de la Universidad de Costa Rica a través de un geo visualizador, el mapa web se ve de la siguiente manera: 
 
**Figura 2.** Vista del mapa web de los edificios de la finca dos, UCR. 
 
 ![](https://user-images.githubusercontent.com/111781085/190355019-4c0b5748-86be-47c4-8bf1-ea6db0278643.png)

El geo visualizador web, permite también acceder a información general clave, sobre estos edificios, para las personas que los visitan. Por ejemplo, la Facultad de Ciencias Sociales (ver figura 3) cuenta con hasta 6 pisos, medidas de seguridad, salas de estudio y biblioteca; además, se puede notar que está contigua a auditorios de la Ciudad de la Investigación y frente a la Casa Infantil universitaria (guardería).La información accesible corresponde a lo siguiente (ver figura 3): 
- Nombre
- Categoría
- Cantidad de pisos
- Salidas de emergencia
- Equipo de emergencia
- Soda
- Área de estudio
- Biblioteca
- *[Contacto](https://www.ucr.ac.cr/directorio/) 
 
*En el enlace puede acceder al directorio UCR, para mayor información sobre los edificios y actividades realizadas en estos, en finca dos. 
  
**Figura 3.** Vista de información desplegable en el mapa web, de los edificios de la finca dos, UCR. 
 
 ![](https://user-images.githubusercontent.com/111781085/190358975-0f30c894-9d7a-49f4-a2a7-20c540d5b940.png) 
  
Lo cual, son aspectos clave para que las personas visitantes tengan una mejor y más precisa noción de la localización y las características del edificio al que necesitan ingresar, en relación con sus necesidades, como comer, estudiar, reunirse en lugares de estudio grupales, entre otros. 
 
## Discusión y conclusiones. 
Durante la redacción de este trabajo, se reflexionó sobre algunos atributos que pudieron contemplarse en el levantamiento de los datos y que, al igual que los mostrados, tienen carácter de importancia. Como lo son: disponibilidad de áreas de lactancia, accesibilidad para las personas con capacidades físicas diversas (discapacidad), ofrecimiento de servicios, áreas de ocio. Sin embargo, se considera positivo ofrecer a las personas un mini directorio telefónico, con lo cual, si bien ya no se facilitó esta información de primera mano, pueden realizar las consultas de interés a ese medio de contacto. 
 
Se puede concluir que, por medio de la recolección estratégica de datos procedentes del mundo real, que están vinculados a una referencia espacial, y su procesamiento con sistemas de información geográfica, es posible ofrecer productos como este geo visualizador web de un mapa que facilita la representación de esos elementos espaciales o fenómenos de otra índole, que no se perciben a simple vista en el paisaje arquitectónico. Permitiendo una mayor aproximación y enriquecimiento en la comprensión de la realidad social que resguardan los elementos estructurales de un espacio geográfico. 
 
## Referencias. 
Vida, M., Moreno, A. y Cañada, R. (2011). *Geovisualización avanzada para la exploración de patrones y relaciones socio-ambientales con SIG: aplicación a la ciudad de Madrid.* INEGI. México. Recuperado de [enlace a referencia](https://n9.cl/fd7uk) 
 
