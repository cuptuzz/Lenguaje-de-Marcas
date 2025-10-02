 
# Curso de Lenguaje de Marcas - Módulo 
 
  
 
**Alumno: Ugo Pérez Ruiz
 
**Grupo:** 1º ASIR
 
**Módulo relacionado:** Lenguaje de marcas y sistemas de gestión de información
 


## ==Módulo 01 - Características de los lenguajes de marcas==

**|-- 01 Recursos/**

[[Características de los lenguajes de marcas.pdf]]
![[Características de los lenguajes de marcas.pdf]]
---
- **Posibles Preguntas para examen:**

	-  ¿Para qué se crearon los lenguajes de marcas?  
		- Para organizar y estructurar información.
	-  ¿Cuándo se creó el primer lenguaje de marcas? ¿Quién lo creó?
		- En los años 1960, IBM desarrolló GML (Generalized Markup Language)
	-  ¿Cuál era la idea principal de los lenguajes de marcas?
		-  Separar el contenido de su presentación visual.
	- ¿Qué nos llevó a los lenguajes de marcas que conocemos hoy en día?
		- SGML (Standart Generalized Markup Language) en los años 80.
	- ¿Qué es exactamente un lenguaje de marcas?
		- Es un sistema que utiliza **etiquetas** para definir la estructura, significado y el formato de la información en un documento.


---
## **Elementos Fundamentales de los Lenguajes de Marcas**

>Hay 3 elementos fundamentales:

1.  **Las etiquetas** Son las marcas que delimitan el contenido. Se escriben entre corchetes angulares: <**etiqueta**>
2.  **Los elementos** Un elemento incluye la etiqueta de apertura, el contenido y la etiqueta de cierre. Es la **unidad básica** de información.
3. **Los atributos** Proporcionan **información adicional** sobre los elementos. Van dentro de la etiqueta de apertura.
---
## **Características comunes de los lenguajes de marcas**

- **- Estructura jerárquica:**
	- Los elementos se organizan en una estructura de árbol donde cada elemento puede contener otros elementos. Esta jerarquía permite representar relaciones complejas de información de manera ordenada y lógica, facilitando tanto el procesamiento automático como la compresión humana.


- **Formato de texto plano:**
	- Se escriben en texto simple, sin formato binario, lo que los hace legibles por humanos y editables con cualquier editor de texto. Esta característica facilita la depuración, el mantenimiento y la colaboración entre desarrolladores.

- **Extensibilidad:**
	- Muchos lenguajes de marcas permiten definir nuevos elementos y atributos según las necesidades específicas del proyecto. Esta flexibilidad los convierte en herramientas poderosas para dominios especializados que requieren vocabularios particulares.

- **Sintaxis bien definida:**
	- Cada lenguaje tiene reglas estrictas sobre cómo escribir las etiquetas, qué elementos pueden contener otros elementos, y cómo se estructuran los atributos. Esta consistencia sintáctica es fundamental para que los procesadores puedan interpretar correctamente el documento.

- **Independencia de plataforma:**
	- Funcionan en cualquier sistema operativo y pueden ser procesados por diferentes aplicaciones. Esta universalidad es clave para la interoperabilidad en entornos heterogéneos y para el intercambio de información entre sistemas diversos.

- **Validación automática:**
	- Pueden verificarse automáticamente contra esquemas o definiciones que establecen qué elementos son válidos, sus atributos permitidos y la estructura correcta. Esta capacidad de validación es esencial para mantener la calidad y consistencia de los documentos.
---
## **Ventajas de los Lenguajes de Marcas**

- **Separación de contenido y presentación:**
	- El contenido (texto, datos) se mantiene independiente del diseño visual. Esto facilita el mantenimiento, la reutilización y permite que un mismo documento tenga diferentes presentaciones (web, impresión, móvil, etc.).

- **Intercambio de datos estructurados:**
	- Sirven como lenguaje común entre sistemas distintos, lo que mejora la interoperabilidad. Son fundamentales en aplicaciones distribuidas y servicios web.

- **Búsqueda y procesamiento eficiente:**
	- La estructura definida permite realizar búsquedas precisas y procesamientos automáticos. Los motores de búsqueda comprenden mejor el contenido y los programas pueden extraer información específica fácilmente.


## **Clasificación por propósito**

![[Captura de pantalla 2025-10-02 223752 1.png]]


## **Clasificación por Flexibilidad**

#### <span style="color:#008000">Lenguajes Fijos</span>

Tienen un conjunto **predefinido y limitado** de elementos y atributos:

- **HTML: ** Vocabulario específico para páginas web.
- **Latex**: Composición de documentos científicos, con comandos predefinidos.
- **RTF:** Desarrollado por Microsoft para representar documentos con formato (fuentes, colores, estilos, etc.).
> [!note] - Son más fáciles de aprender pero menos adaptables a necesidades específicas.

#### <span style="color:#008000">Lenguajes Extensibles</span>

Permiten **definir elementos personalizados** según las necesidades:

- **XML:** Totalmente personalizable
- **SGML:** Base para crear otros lenguajes
- **Custom HTML:** Con web components

>[!tipe] - Ofrecen máxima flexibilidad pero requieren mayor planificación y conocimiento teórico

