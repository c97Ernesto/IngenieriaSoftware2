## Que es un proceso de software?
**Es un conjunto de actividades y resultados asociados que producen un producto de software.**

- **Qué es el modelo?**
  - Es lo que representa a nivel abstracto ese proceso.

### Actividades fundamentales de los modelos.
- Especificación del software:
  - Técnicas de elicitación.
  - Especificación de Requerimientos.
- Desarrollo del Software.
- Validación del Software.
- Evolución del Software.

## Elicitación de Requisitos
**Es el proceso de adquirir ("eliciting") [sonsacar] todo el conocimiento relevante necesario para producir un modelo de los requerimientos de un dominio del problema.**

_**Objetivos:**_
- Conocer el dominio del problema para poder comunicarse con clientes y usuarios para poder entender sus necesidades.
- Conocer el sistema actual (manual o informatizado).
- Identificar las necesidades, tanto explícitas como implícitas, de clientes y usuarios, además de las expectativas sobre el sistema a desarrollar.

### Muestreo de la documentación, los formularios y los datos existentes.
**Recolección de hechos a partir de la documentación existente**

**_Qué tipo de documentos puden darnos más información acerca del sistema?_**
- Organigramas
- Memos, notas internas, minutas, registros contables.
- Solicitudes de proyectos de sistemas de información anteriores.

### Observación del ambiente de trabajo.

El analista se convierte en observador de las personas y actividades, con el objetivo de aprender acerca del sistema.

Lineamientos de observación:
- Determianr quien y cuando será observado.
- Obtener el permiso de la persona y explicar el porqué será observado.
- Mantener bajo perfil.
- Tomar nota de los observado.
- Revisar las notas con la persona apropiada.
- No interrumpir a la persona en su trabajo.

### Visitas al sitio...

### Cuestionarios...

### Entrevistas...

### JRP...

### Brainstorming...
  
## Requerimientos
1. Solicitud.
2. Definición.
3. Análisis.
4. Especificación.

#### Funcionales:
- Definen el comportamiento del sistema.
- Describen las tareas que el sistema debe realizar.
- Al definir un requisito funcional es importante mantener el equilibrio entre la excesiva generalidad, y el exceso de detalle con descripciones innecesarias o redundantes.

#### No funcionales:
- Definen aspectos, que sin ser funcionalidades, (tareas que el sistema debe realizar) resultan deseables desde el punto de vista del usuario.
- También se pueden ver como restricciones:
  - Tiempos de respuesta.
  - Características de usabilidad.
  - Facilidad de mantenimiento.
  - Otros.

### Especificación de Requerimientos
<u>Documento **ConOps**</u>: normalizado por el estándar **IEE Std. 1362-1998**.
- Está dirigido a los usuarios, describiendo las características de un sistema propuesto desde el punto de vista del usuario.
- Esta Descripción del Sistema **es el medio de comunicación** que recoge la visión general, cualitativa y cuantitativa de las características del sistema; compartido por la parte cliente y desarrolladora.
- Ofrece un formato específico para la confección de las descripciones del sistema
- No especifíca técnicas exactas, sino que proporciona las líneas generales que deben respetarse. Es una **guía de referencia**.
- Identifica los elementos que al menos debe incluir una **descripción del sistema**. El usuario puede agregar otros elementos, agregando cláusulas y sub-cláusulas.

<u>Documento **SRS (ERS)**</u>: normalizado por el estándar **IEE Std. 830-1998**.
- Es la especificación de las funciones que realiza un determinado producto de software, programa o conjunto de programas en un determinado entorno.
- El documento de especificación de requisitos puede desarrollarlo personal representativo de la parte desarrolladora, o de la parte cliente; si bien es aconsejable la intervención de ambar partes.
- El desarrollo futuro del sistema depende en gran medida de éste documento.

## IEE 830-SRS.
### Práctica recomendada por IEEE para especificaciones de requisitos de software:

#### Alcance:
- Brindar una colección de buenas prácticas para escribir especificaciones de requerimientos de software (SRS). Se describen los contenidos y las cualidades de una buena especificación de requerimientos.

#### Naturaleza del SRS
- Es una especificación para un producto de software particular. El SRS es escrito por uno o más representantes del equipo de desarrollo y uno o más representantes de la parte cliente o ambos.

#### Ambiente SRS
- El software puede contener toda la funcionalidad del proyecto o puede ser parte de un sistema más grande. En el último caso habrá un SRS que declarará las interfaces entre el sistema y su software desarrollado, y pondrá que función externa y requerimientos de funcionalidad tienen con el software desarrollado.

#### Correcto
- Un SRS es correcto si, y solo si, cada requisito declarado se encuentra en el software.

#### No ambigüo
- Un SRS es inequívoco si, y solo si, cada requisito declarado tiene solo una interpretación.

#### Completo
- Un SRS está completo si, y solo si, se reconoce cualquier requisito externo impuesto por una especificación del sistema.

#### Consistente
- La consistencia refiere a la consistencia interior. Si un SRS no está de acuerdo con algún documento del nivel superior, como una especificación de requerimientos del sistema, entonces no es consistente.

#### Priorizado
- Un SRS es priorizado por la importancia de sus requerimientos particulares.

#### Comprobable
- Un SRS es comprobable si, y solo si, cada requisito declarado es comprobable. Un requisito es comprobable si, y solo si, existe algún proceso con que una persona o máquina puede verificar que el producto de software reúne el requisito. En general cualquier requisito ambigüo no es comprobable.

#### Modificable
- Un SRS es modificable si, y solo si, su estructura y estilo

#### Trazabilidad
- Claridad del origen de cada requerimiento y su trazabilidad hacia los requerimientos futuros desarrollados.

#### Preparación conjunta del SRS
- El SRS se debe preparar en conjunto con las partes intervinientes para lograr un buen acuerdo entre las partes.

#### Evolición del SRS
- El SRS debe evolucionar conjuntamente con el software, registrando los cambios, los responsables y aceptación de los mismos.

#### Prototipos
- El uso de prototipos se utiliza frecuentemente para la definición de requerimientos.

#### Diseño incorporado en el SRS
- El SRS puede incorporar los atributos o funciones externos al sistema, en particular las que describen el diseño para interactuar entre los subsistemas.

#### Requerimientos incorporados en el SRS
- Los detalles particulares de los requerimientos son anexados como documentos externos (CU, Plan de proyecto, Plan de aseguramiento de calidad, etc).

### Partes de un SRS
1. **INTRODUCCIÓN**
    - Propósito
    - Alcance
    - Referencias

2. **DESCRIPCIÓN GENERAL**  
Esta sección debe describir los factores generales que afectan el producto y sus requerimientos. No declara los requerimientos específicos.
    - Perspectiva del producto
    - Funcionalidad del producto
    - Características de los usuarios
    - Evolición previsible del sistema

3. **REQUISITOS NO FUNCIONALES**  
Debe contener todos los requerimientos no funcionales del software a un nivel de detalle para permitirles a los diseñadores diseñar el sistema, y a los auditores probar que el sistema satisface esos requerimientos.
    - Requisitos de rendimiento
    - Seguriddad
    - Portabilidad

4. **MANTENIMIENTO**  
Identifiación de tipo de mantenimiento necesario del sistema.  
Especificaciónde quien debe realizar las tareas de mantenimiento, por ejemplo, usuarios, o un desarrollador.    
Especificación de cuando deben realizarse las tareas de mantenimiento. Por ejemplo, generación de estadísitcas de acceso semanales y mensuales.


5. **APÉNDICE**    
Puede contener todo tipo de información relevante para el SRS pero que, propiamente, no forma parte del mismo.    
Por ejemplo: Casos de Uso, Historias de Usuarios.