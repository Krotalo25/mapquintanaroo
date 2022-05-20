# MAPA BASE DE LIMITES CONSTITUCIONALES Y MUNICIPALES DE QUINTANA ROO PARA ESTUDIOS AMBIENTALES

Mapa base de limites constitucionales y municipales del estado de Quintana Roo para estudios ambientales

#### Identificación del conjunto de datos espaciales o producto: 
mapa_base_quintana_roo

#### Título del conjunto de datos espaciales: 
LÍMITES MUNICIPALES CONSTITUCIONALES DEL ESTADO DE QUINTANA ROO CON LA DELIMITACIÓN DE COSTA DEL INEGI.

#### Fecha de referencia del conjunto de datos espaciales: 
09 de febrero de 2022

#### Localización geográfica del conjunto de datos espaciales (por 4 coordenadas o por identificador geográfico):
QUINTANA ROO

#### Idioma del conjunto de datos espaciales: 
ES-Español

#### Categoría del tema del conjunto de datos espaciales: 
Base de imágenes de mapas de la cobertura de la tierra. 

#### Grupo de datos del conjunto de datos espaciales o productos: 
Grupo de datos de recursos naturales y clima.

#### Palabra clave: 
Quintana Roo, Cambio climático, medio ambiente.

#### Forma de presentación de los datos espaciales: 
Mapa Digital.

#### Frecuencia de mantenimiento y actualización: 
Irregular.

#### Conjunto de caracteres: 
UTF-8

#### Propósito: 
Contar con una capa base de los límites constitucionales del Estado de Quintana Roo y de sus municipios, que cuente con la delimitación de la línea de costa. Esta capa será utilizada como referencia para realizar análisis geoespaciales de la distribución de las coberturas del Sistema de Monitoreo Forestal (SAMOF) de la entidad.

#### Descripción del conjunto de datos espaciales o producto:
Se tomaron como base los límites políticos constitucionales del Estado y sus Municipios decretados en la reforma de la CONSTITUCIÓN POLÍTICA DEL ESTADO LIBRE Y SOBERANO DE QUINTANA ROO, Publicada en el Periódico Oficial del Estado el 24 de diciembre del 2021.
Los límites políticos constitucionales de algunos municipios tienen desfases (solapamientos y vacíos) entre el municipio de Solidaridad y el municipio de Tulum, así como entre Solidaridad y el Municipio de Puerto Morelos, derivado de lo anterior, se realizó un ajuste en los límites Sur y Norte del municipio de Solidaridad tomando como referencia los límites del municipio de Tulum y de Puerto Morelos respectivamente, al ser estos municipios de más reciente creación. Estos desfases y ajustes realizados se ejemplifican en las figuras siguientes:

Para detallar aún más el proceso de ajuste mencionado, en la tabla siguiente se muestran los vértices constitucionales del Municipio de Solidaridad que aparecen en las figuras presentadas previamente, indicando sus coordenadas, la distancia de desfase con el vértice correspondiente de Tulum, y las coordenadas a las cuales fueron ajustados los vértices para evitar solapamientos y vacíos:

Aunado a lo anterior, los límites políticos constitucionales descritos no delimitan la línea de costa, por tal motivo esto fue tomado de la capa vectorial Marco Geoestadístico, Censo de Población y Vivienda 2020 Integrado del Proyecto Básico de Información 2020 elaborado por el INEGI. En las figuras siguientes se observa cómo al trazar los municipios con los vértices constitucionales no se cuenta con la línea de costa, y cómo esta fue tomada de la capa del INEGI.

Así también, al observarse una discrepancia entre los límites internacionales señalados en la CONSTITUCIÓN POLÍTICA DEL ESTADO LIBRE Y SOBERANO DE QUINTANA ROO y en el Proyecto Básico del INEGI 2020, se decidió ajustar los vértices constitucionales del municipio de Othón P. Blanco colindantes con el límite internacional, a los señalados en las capas del INEGI, es decir, que fueron tomados los límites internacionales señalados en las capas del INEGI en sustitución de los límites constitucionales del Estado; esto se realizó con la finalidad de que la capa resultante pueda ser empleada para realizar análisis espaciales con productos nacionales. En este sentido, los vértices constitucionales de Othón P. Blanco No. 77 al 89 fueron modificados alineándose al límite internacional que establece el INEGI. Este proceso de ajuste se ejemplifica a continuación con el vértice No. 89 ubicado en el extremo inferior izquierdo del polígono constitucional de Othón P. Blanco, el cual se encontraba con un desfase de 172 metros:

Por otra parte, la colindancia constitucional entre los municipios de Othón P. Blanco y Bacalar en la porción del espejo de agua de la Laguna de Bacalar, está representada únicamente por dos vértices, formando una línea recta que atraviesa dicho cuerpo de agua. Por este motivo, los polígonos de ambos municipios fueron ajustados adicionando la división de la capa del Proyecto Básico del INEGI, la cual se adecua al litoral de la Laguna:

#### Descripción de entidades y atributos:
Polígonos de los 11 municipios del Estado de Quintana Roo.
	Dominio de Valores:
	CVE_MUN: Es la clave asignada a los municipios del 001 al 011
	MUNICIPIO: Es el nombre del municipio
	HECTAREAS: Es la superficie del municipio en hectáreas
	KM2: Es la superficie del municipio en Kilómetros cuadrados

#### Uso específico: 
Esta capa de la superficie del estado de Quintana Roo se emplea para realizar análisis geoespaciales en materia de ciencias ambientales. Esta basado en los límites señados en la constitución del estado, pero no se ocupa para delimitar políticamente los municipios del estado. Emplearlo satisface la necesidad de contar con una geometría libre de traslapes y vacíos espaciales que ocurren si se toman los vértices de los decretos. De la misma forma esta capa contiene la línea de costa del marco geoestadístico nacional del INEGI del año 2020 y sus límites internacionales, haciendo compatible realizar análisis con los productos nacionales sin obtener geometrías nulas o inválidas.

#### Sistema de referencia de coordenadas de la capa: 
EPSG: 6371  - Mexico ITRF2008 / UTM zone 16N 

#### Software empleado: 
QGIS versión 3.16.7

#### Unidad del estado responsable del conjunto de datos espaciales o producto:
#### Nombre de la persona de contacto: 
Miguel Angel suárez Sarabia
#### Nombre de la organización: 
Dirección de cambio climático de la Secretaría de Ecología y Medio Ambiente del estado de Quintana Roo. 
#### Puesto del contacto: 
Director de Cambio Climático.
#### Teléfono: 
983 1292827 Ext. 210
#### Correo electrónico: 
dcc.sema14@gmail.com
#### Rol: 
Proveedor del recurso
#### Tipo de representación espacial: 
Vector

#### Recurso en línea: 
http://sema.qroo.gob.mx/cartografia/

##### Servidor cartográfico de la Secretaría de Ecología y Medio Ambiente del estado de Quintana Roo.
