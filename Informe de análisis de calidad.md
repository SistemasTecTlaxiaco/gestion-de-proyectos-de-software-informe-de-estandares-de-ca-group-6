# INFORME DE ANÁLISIS DE CALIDAD: STELLAR Y DRIPS

**Proyecto:** Open Hub Tec

**Sistema:** Sistema de apoyo para vendedores de tenates artesanales de palma

**Metodología:** eduScrum

**Marco de calidad:** CMMI y MoProSoft

**Región:** Heroica Ciudad de Tlaxiaco, Oaxaca, México

---

# 1. INTRODUCCIÓN

El presente informe tiene como finalidad analizar los requerimientos técnicos y de calidad relacionados con las tecnologías Web3 Stellar y Drips, considerando su posible relación con el proyecto **Open Hub Tec**, un sistema de apoyo para vendedores y artesanas dedicadas a la elaboración y comercialización de tenates artesanales de palma en la región de la Mixteca.

El análisis parte del **Plan de Calidad de Open Hub Tec**, en el cual se establecieron prácticas relacionadas con requisitos, criterios de aceptación, pruebas, prevención de errores, corrección, trazabilidad, usabilidad, seguridad y adaptación a condiciones de conectividad limitada.

Stellar es una red blockchain que cuenta con **Soroban**, su plataforma de contratos inteligentes, mientras que el ecosistema de financiamiento de Stellar contempla programas como el Stellar Community Fund (SCF). Actualmente, el SCF ofrece distintas vías de financiamiento para proyectos que construyen sobre Stellar y Soroban, y los proyectos elegibles pueden acceder a mecanismos de auditoría de seguridad.

Por otra parte, Drips se relaciona con el financiamiento de proyectos de código abierto mediante mecanismos de distribución y streaming de fondos. Por ello, su análisis no debe limitarse a explicar blockchain, sino que debe considerar aspectos de calidad, transparencia, seguridad, gestión del código y riesgos.

El propósito de este informe es determinar cómo estos elementos pueden relacionarse con las prácticas de calidad de Open Hub Tec, tomando en cuenta las condiciones reales de operación de la región Mixteca y evitando incorporar tecnologías Web3 de manera innecesaria.

---

# 2. OBJETIVO GENERAL

Analizar los requisitos técnicos, de calidad, seguridad, transparencia y gestión de código abierto relacionados con Stellar y Drips, para determinar cómo pueden adaptarse al proyecto Open Hub Tec mediante las prácticas establecidas en su Plan de Calidad, considerando las condiciones de conectividad limitada de la región Mixteca.

---

# 3. OBJETIVOS ESPECÍFICOS

1. Identificar las principales características técnicas de Stellar y Drips relacionadas con la calidad del software.
2. Analizar la importancia del código abierto, las pruebas, la documentación, la seguridad y la trazabilidad dentro de estas tecnologías.
3. Adaptar las métricas y prácticas de calidad de Open Hub Tec al posible uso de tecnologías Web3.
4. Identificar riesgos técnicos, de seguridad, privacidad y transparencia relacionados con blockchain.
5. Relacionar la ingeniería de software con los mecanismos de financiamiento Web3, particularmente el financiamiento on-chain y el streaming de fondos.
6. Aplicar el análisis a las historias de usuario HU01, HU02, HU03 y HU04 del proyecto Open Hub Tec.

---

# 4. MATERIALES Y FUENTES UTILIZADAS

Para realizar el análisis se consideran los siguientes materiales:

- Plan de Calidad de Open Hub Tec.
- Historias de usuario HU01, HU02, HU03 y HU04.
- Documentación de Stellar Development Foundation.
- Documentación relacionada con Soroban.
- Información del Stellar Community Fund.
- Información técnica de Drips.
- CMMI Development.
- MoProSoft, basado en la NMX-I-059/02-NYCE-2016.
- Repositorio y documentación del proyecto cuando corresponda.
- Herramientas de inteligencia artificial como apoyo para investigación y organización de información.

CMMI Development proporciona buenas prácticas orientadas a mejorar la capacidad de las organizaciones para desarrollar productos y servicios de calidad y reducir defectos y retrabajo.

MoProSoft, por su parte, establece procesos y prácticas para la gestión y desarrollo de software, buscando que los procesos sean organizados, documentados, trazables y medibles.

---

# 5. DESEMPEÑO TÉCNICO: ANÁLISIS DE STELLAR Y DRIPS

## 5.1 Análisis técnico de Stellar

Stellar es una red blockchain orientada a operaciones y aplicaciones descentralizadas. Dentro de su ecosistema se encuentra **Soroban**, plataforma de contratos inteligentes que permite desarrollar aplicaciones sobre Stellar. La plataforma también cuenta con herramientas y recursos para desarrollo, pruebas y despliegue.

Para Open Hub Tec, el interés de Stellar no estaría solamente en utilizar una blockchain, sino en determinar si alguna función del sistema realmente requiere características de descentralización, trazabilidad o financiamiento que justifiquen su integración.

### Requisitos de calidad identificados

| Requisito | Relación con la calidad |
|---|---|
| Código controlado y documentado | Permite conocer qué versión se está utilizando y facilitar revisiones. |
| Pruebas antes del despliegue | Reduce la posibilidad de errores en producción. |
| Seguridad | Es necesaria para evitar vulnerabilidades en contratos y componentes relacionados. |
| Auditoría | Permite revisar el código desde una perspectiva de seguridad antes de una implementación importante. |
| Trazabilidad | Permite relacionar cambios, versiones, requisitos y evidencias. |
| Documentación | Facilita mantenimiento y revisión del sistema. |
| Uso significativo de Stellar | Evita agregar blockchain únicamente para aparentar una integración Web3. |

Stellar cuenta actualmente con un **Soroban Security Audit Bank**, mediante el cual determinados proyectos financiados por SCF pueden acceder a auditorías de seguridad realizadas por firmas especializadas. La propia documentación señala que la preparación para una auditoría requiere código estable, documentación completa y preparación para revisión.

Por lo tanto, una posible integración de Open Hub Tec con Stellar tendría que considerar la seguridad desde las primeras etapas y no únicamente después de terminar el desarrollo.

---

## 5.2 Stellar Community Fund

El **Stellar Community Fund (SCF)** es un programa de financiamiento dirigido a proyectos que construyen sobre Stellar. Actualmente contempla distintas modalidades dentro de su Build Track y puede proporcionar financiamiento de hasta 150,000 XLM para proyectos que buscan pasar de una idea validada hacia un lanzamiento en Stellar.

Desde el punto de vista de calidad, esto significa que un proyecto que pretenda utilizar este tipo de financiamiento debe demostrar que existe un desarrollo real y que su integración con Stellar tiene una función significativa.

Por lo tanto, Open Hub Tec no debería integrar Stellar solamente para intentar obtener financiamiento. Primero tendría que existir una necesidad funcional y posteriormente comprobar que la tecnología aporta valor al proyecto.

---

## 5.3 Análisis técnico de Drips

Drips se relaciona con el financiamiento de proyectos de código abierto mediante mecanismos de distribución y streaming de fondos.

Desde la perspectiva de calidad, el interés principal está en la relación entre:

**código abierto → dependencias → mantenimiento → financiamiento → transparencia**

Esto permite analizar la calidad del software no solamente como una característica técnica, sino también como un elemento relacionado con la sostenibilidad de un proyecto.

### Requisitos de calidad relacionados

| Requisito | Importancia |
|---|---|
| Repositorio público | Permite revisar el desarrollo del proyecto. |
| Control de versiones | Permite identificar cambios y mantener trazabilidad. |
| Dependencias identificadas | Facilita conocer de qué componentes depende el software. |
| Documentación | Ayuda a comprender instalación, funcionamiento y mantenimiento. |
| Transparencia financiera | Permite conocer el flujo de fondos registrado en la red. |
| Seguridad | Reduce riesgos relacionados con contratos, wallets y dependencias. |

En este caso, el código abierto no debe interpretarse como una garantía automática de calidad. Que el código sea público permite revisarlo, pero sigue siendo necesario aplicar pruebas, revisión de código, control de versiones y mecanismos de seguridad.

---

## 5.4 Comparación técnica

| Aspecto | Stellar | Drips |
|---|---|---|
| Propósito relacionado con el proyecto | Construcción y financiamiento de aplicaciones sobre Stellar | Financiamiento de proyectos y dependencias de código abierto |
| Tecnología principal | Blockchain Stellar y Soroban | Infraestructura Web3 para distribución y streaming |
| Calidad del software | Pruebas, documentación, seguridad y auditoría | Código abierto, dependencias, control y transparencia |
| Código abierto | Relevante para el desarrollo y revisión | Elemento central del modelo de proyectos financiables |
| Seguridad | Especialmente importante en contratos inteligentes | Importante por contratos, fondos y dependencias |
| Transparencia | Puede aprovechar registros verificables | El modelo de financiamiento busca trazabilidad de los flujos |
| Riesgo principal | Vulnerabilidades en contratos o integración incorrecta | Dependencia de contratos, código externo y exposición de información |
| Aplicación en Open Hub Tec | Solo si aporta una función real | Como posible mecanismo de financiamiento, si resulta viable |

---

# 6. ADAPTACIÓN A SITUACIONES Y CONTEXTOS COMPLEJOS

La calidad de Open Hub Tec no puede evaluarse únicamente considerando las características técnicas de blockchain. También debe considerar las condiciones en las que realmente utilizarán el sistema sus usuarios.

La región Mixteca puede presentar condiciones de conectividad diferentes a las consideradas en sistemas diseñados exclusivamente para ambientes con conexión permanente. Por ello, las funciones principales del sistema deben priorizar la continuidad de operación y la conservación de información.

---

## 6.1 Conectividad limitada

Uno de los principales puntos de adaptación consiste en evitar que una conexión temporalmente inexistente impida registrar información básica.

Por ejemplo, una artesana debería poder registrar:

- Tipo de tenate.
- Medida.
- Material.
- Precio.
- Existencia.

sin que una interrupción temporal de Internet provoque la pérdida de la información.

En caso de utilizarse posteriormente una integración Web3, esta debería funcionar como una capa adicional y no como una dependencia que bloquee las funciones principales.

---

## 6.2 Propuesta de sincronización

La adaptación propuesta sería:

**Usuario → almacenamiento local → recuperación de conexión → validación → sincronización → registro externo cuando corresponda**

Esto permitiría separar las operaciones normales del sistema de aquellas que necesiten conexión.

La sincronización debería considerar:

- Evitar registros duplicados.
- Validar la información antes de sincronizar.
- Identificar registros pendientes.
- Conservar la información si ocurre una interrupción.
- Registrar errores de sincronización.
- Permitir revisar posteriormente el estado de la operación.

---

# 7. ADAPTACIÓN DE LAS MÉTRICAS DE CALIDAD

Las métricas existentes deben adaptarse para considerar tanto el funcionamiento tradicional del sistema como los riesgos asociados a Web3.

| Métrica | Aplicación en Open Hub Tec |
|---|---|
| Cumplimiento de criterios | Verificar que cada HU cumpla sus criterios antes de aprobarse. |
| Cobertura de pruebas | Probar funciones normales, errores y situaciones sin conexión. |
| Integridad de datos | Comprobar que precios, medidas y características no se alteren. |
| Duplicados | Verificar que una sincronización no genere registros repetidos. |
| Disponibilidad offline | Medir qué funciones críticas continúan funcionando sin conexión. |
| Seguridad | Revisar accesos, datos y posibles vulnerabilidades. |
| Trazabilidad | Relacionar cambios con historias, versiones y evidencias. |
| Corrección | Registrar defectos encontrados y horas utilizadas para corregirlos. |

---

# 8. APLICACIÓN A LAS HISTORIAS DE USUARIO

Para demostrar que el análisis no es solamente teórico, se relacionan los requisitos Web3 con las historias reales de Open Hub Tec.

| Historia | Relación con calidad | Adaptación propuesta |
|---|---|---|
| **HU01. Tiempo y costo para determinar precio mínimo** | Integridad y exactitud de información | Validar cálculos y conservar registros antes de cualquier sincronización. |
| **HU02. Existencias y ventas** | Consistencia y trazabilidad | Evitar duplicados cuando los datos se sincronicen después de una pérdida de conexión. |
| **HU03. Catálogo digital** | Disponibilidad y calidad de información | Mantener información previamente guardada para consultas cuando no exista conexión. |
| **HU04. Características del tenate** | Integridad y completitud | Validar tipo, medida, material y precio antes de guardar o sincronizar. |

Es importante señalar que estas adaptaciones son **propuestas de diseño y calidad**. No se debe afirmar que Open Hub Tec ya utiliza Stellar o Drips si dicha integración todavía no ha sido implementada.

---

# 9. PENSAMIENTO CRÍTICO MEDIANTE TECNOLOGÍAS

## 9.1 Seguridad

El uso de blockchain no elimina automáticamente los riesgos de seguridad.

En un contrato inteligente, un error puede producir consecuencias diferentes a las de un error en una aplicación convencional. Por ello, las pruebas y revisiones deben realizarse antes de colocar componentes importantes en una red pública.

Stellar dispone de mecanismos de auditoría de seguridad para proyectos elegibles de SCF, además de herramientas y revisiones especializadas.

Para Open Hub Tec se propone considerar:

1. Revisión de código.
2. Pruebas unitarias.
3. Pruebas de integración.
4. Análisis de vulnerabilidades.
5. Revisión de dependencias.
6. Auditoría antes de un despliegue crítico.

---

## 9.2 Privacidad de la información

La transparencia de blockchain puede ser útil para verificar operaciones, pero no significa que toda la información de los usuarios deba hacerse pública.

En Open Hub Tec se manejan datos relacionados con:

- Productos.
- Precios.
- Ventas.
- Existencias.
- Información de las personas que utilizan el sistema.

Por ello, antes de registrar información en una blockchain debería determinarse:

**¿Es necesario que este dato sea público?**

Si la respuesta es no, la información podría mantenerse fuera de la cadena y utilizar únicamente mecanismos de verificación cuando realmente sean necesarios.

---

## 9.3 Código abierto

El código abierto facilita la revisión y colaboración, pero también implica responsabilidades.

Un proyecto debe controlar:

- Quién modifica el código.
- Qué cambios se aceptan.
- Qué dependencias se incorporan.
- Qué vulnerabilidades tienen esas dependencias.
- Qué información queda expuesta.
- Qué versión se considera estable.

Por esta razón, **“ser open source” no debe utilizarse como sinónimo de “ser seguro”**.

La calidad debe comprobarse mediante procesos, pruebas y evidencias.

---

# 10. RIESGOS IDENTIFICADOS

| Riesgo | Consecuencia | Medida de prevención |
|---|---|---|
| Interrupción de Internet | Pérdida o retraso de información | Almacenamiento local y sincronización posterior |
| Sincronización duplicada | Datos incorrectos | Identificadores únicos y validación |
| Error en contrato inteligente | Operación incorrecta | Pruebas y auditoría |
| Vulnerabilidad de dependencia | Compromiso de seguridad | Revisión de dependencias |
| Exposición de información | Pérdida de privacidad | Clasificación de datos |
| Uso innecesario de blockchain | Mayor complejidad | Justificar cada integración |
| Falta de capacitación | Errores de operación | Capacitación y documentación |
| Dependencia de servicios externos | Interrupción de funciones | Diseñar funciones críticas independientes |

---

# 11. ACTIVIDADES Y CONOCIMIENTOS INTERDISCIPLINARIOS

La integración entre calidad de software y Web3 requiere relacionar conocimientos de diferentes áreas.

### Ingeniería de software

Se utilizan:

- Ingeniería de requisitos.
- Pruebas.
- Gestión de configuración.
- Seguridad.
- Control de versiones.
- Métricas de calidad.
- Gestión de riesgos.

### Web3

Se consideran:

- Blockchain.
- Contratos inteligentes.
- Financiamiento on-chain.
- Streaming de fondos.
- Wallets.
- Transparencia de transacciones.

### Contexto económico y social

En Open Hub Tec también debe considerarse:

- Comercialización de tenates.
- Control de precios.
- Ventas.
- Disponibilidad de productos.
- Necesidades de las artesanas.
- Conectividad regional.

La integración de estos conocimientos permite que la tecnología se analice desde su utilidad real y no solamente desde sus características técnicas.

---

# 12. RELACIÓN ENTRE CALIDAD Y FINANCIAMIENTO WEB3

El financiamiento Web3 puede relacionarse directamente con la calidad porque un proyecto que busca financiamiento necesita demostrar que existe un desarrollo verificable.

Por ejemplo:

**Criterios de aceptación**

↓

**Desarrollo**

↓

**Pruebas**

↓

**Evidencia**

↓

**Entregable verificable**

↓

**Posibilidad de demostrar avance ante un mecanismo de financiamiento**

Esto convierte las prácticas de calidad en una herramienta para demostrar el estado real del proyecto.

En Stellar, el SCF contempla financiamiento para proyectos que desarrollan sobre su ecosistema y actualmente cuenta con mecanismos de apoyo a la seguridad.

---

# 13. COSTO DE CALIDAD

Para este análisis se conserva el criterio establecido en la práctica:

**Tarifa: $150 MXN por hora.**

Los siguientes valores son **estimaciones de trabajo**, no resultados reales.

| Historia | Prevención | Costo prevención | Corrección | Costo corrección | Costo total | % prevención |
|---|---:|---:|---:|---:|---:|---:|
| HU01 | 3 h | $450 | 2 h | $300 | $750 | 60% |
| HU02 | 2.5 h | $375 | 1.5 h | $225 | $600 | 62.5% |
| HU03 | 3.5 h | $525 | 2.5 h | $375 | $900 | 58.3% |
| HU04 | 3 h | $450 | 2 h | $300 | $750 | 60% |
| **Total** | **12 h** | **$1,800** | **8 h** | **$1,200** | **$3,000** | **60%** |

### Fórmulas utilizadas

**Costo de prevención:**

> Horas de prevención × $150

**Costo de corrección:**

> Horas de corrección × $150

**Costo total:**

> Costo de prevención + costo de corrección

**Porcentaje de prevención:**

> Costo de prevención / costo total × 100

Estos valores representan una planeación estimada para analizar cuánto esfuerzo podría destinarse a prevenir problemas frente al esfuerzo necesario para corregirlos.

---

# 14. PROPUESTA DE ACTIVIDADES DE CALIDAD PARA OPEN HUB TEC

Para una posible integración Web3 se proponen las siguientes actividades:

| Actividad | Objetivo |
|---|---|
| Revisión de requisitos | Evitar integrar funciones innecesarias. |
| Revisión de arquitectura | Determinar qué funciones requieren conexión. |
| Pruebas offline | Comprobar funcionamiento sin Internet. |
| Pruebas de sincronización | Evitar pérdida y duplicación de datos. |
| Revisión de código | Detectar errores antes de integrar componentes Web3. |
| Revisión de dependencias | Identificar riesgos externos. |
| Pruebas de seguridad | Detectar vulnerabilidades. |
| Auditoría previa a despliegue | Revisar componentes críticos. |
| Revisión de privacidad | Evitar exponer información innecesaria. |
| Documentación | Facilitar mantenimiento y capacitación. |

---

# 15. INDICADORES PROPUESTOS

Para comprobar posteriormente la calidad del proyecto se pueden utilizar los siguientes indicadores:

| Indicador | Meta propuesta |
|---|---:|
| Historias con criterios de aceptación definidos | 100% |
| Historias probadas | 100% |
| Criterios de aceptación cumplidos | 100% |
| Errores críticos al cierre | 0 |
| Registros duplicados después de sincronización | 0 |
| Datos obligatorios incompletos | ≤ 5% |
| Funciones críticas evaluadas sin conexión | 100% |
| Cambios importantes con evidencia | 100% |
| Componentes Web3 revisados antes de integración | 100% |
| Componentes críticos auditados antes de despliegue | 100% |

Estas metas son **propuestas de evaluación**, por lo que posteriormente deberán compararse con resultados reales.

---

# 16. USO DE INTELIGENCIA ARTIFICIAL

La inteligencia artificial puede utilizarse como herramienta de apoyo durante la elaboración del análisis, pero la información técnica debe verificarse con documentación confiable.

| Actividad | Uso de IA | Verificación |
|---|---|---|
| Investigación de Stellar | Obtener una explicación inicial | Documentación oficial de Stellar |
| Investigación de Drips | Identificar conceptos técnicos | Documentación técnica disponible |
| Comparación | Organizar características | Revisión del equipo |
| Adaptación al proyecto | Proponer relaciones con HU01-HU04 | Revisión del equipo |
| Riesgos | Generar posibles escenarios | Análisis del equipo |
| Redacción | Organizar el informe | Revisión y corrección humana |

La IA se considera un apoyo para investigar, organizar y redactar, pero **no debe considerarse la fuente primaria de los requisitos técnicos**.

---

# 17. RESULTADO DEL ANÁLISIS

A partir de la revisión realizada se identificó que Stellar y Drips introducen consideraciones de calidad diferentes a las de una aplicación convencional.

En Stellar, la seguridad de contratos inteligentes, las pruebas, la documentación y las auditorías adquieren una importancia especial. El ecosistema cuenta con mecanismos específicos de apoyo a auditorías de seguridad para determinados proyectos financiados mediante SCF.

En Drips, el análisis se concentra principalmente en la relación entre código abierto, dependencias, transparencia y financiamiento.

Para Open Hub Tec, la principal adaptación consiste en **no hacer que la tecnología Web3 sea una dependencia de las funciones básicas del sistema**. Las funciones principales relacionadas con productos, precios, existencias y ventas deben mantener una operación adecuada aun cuando exista una interrupción de conectividad.

También se identificó que blockchain no debe utilizarse solamente porque sea una tecnología actual. Cada integración tendría que justificarse mediante una necesidad real del proyecto.

---

# 18. CONCLUSIONES

El análisis realizado permitió comprender que la calidad de software dentro de un proyecto Web3 no depende únicamente de que el sistema funcione correctamente, sino también de aspectos como la seguridad, trazabilidad, gestión del código, documentación, control de cambios y transparencia.

En el caso de Stellar, se identificó que el desarrollo sobre su ecosistema puede requerir prácticas de seguridad más estrictas cuando intervienen contratos inteligentes. La existencia de mecanismos de auditoría dentro del ecosistema demuestra la importancia que tiene la revisión de seguridad antes de determinados despliegues.

En cuanto a Drips, el análisis permitió relacionar el código abierto con mecanismos de financiamiento y distribución de recursos. Sin embargo, la transparencia que ofrecen las tecnologías blockchain también debe analizarse desde el punto de vista de la privacidad y la protección de información.

Para Open Hub Tec, la principal consideración es adaptar estas tecnologías a la realidad del proyecto y no modificar el proyecto únicamente para utilizar blockchain. Las funciones principales relacionadas con los tenates, precios, existencias y catálogo deben conservar su utilidad en condiciones de conectividad limitada.

Finalmente, la integración de CMMI, MoProSoft y conceptos Web3 permite establecer una relación entre calidad de software, seguridad, gestión de proyectos y financiamiento descentralizado. De esta manera, las prácticas de calidad pueden servir no solamente para detectar errores, sino también para generar evidencias de que el desarrollo se realiza de manera organizada, verificable y adecuada al contexto de los usuarios.

---

# 19. REFERENCIAS BIBLIOGRÁFICAS

CMMI Institute. (s. f.). *CMMI Development*.  
https://cmmiinstitute.com/cmmi/dev

Normalización y Certificación NYCE. (s. f.). *Inspección de proceso de desarrollo de software – NMX-I-059/02-NYCE-2016 (MoProSoft)*.  
https://nyce.org.mx/inspeccion-de-software-moprosoft-nmx-i-059-02-nyce-2016/

Stellar Development Foundation. (s. f.). *Grants and Funding*.  
https://stellar.org/grants-and-funding

Stellar Development Foundation. (s. f.). *Soroban Security Audit Bank*.  
https://stellar.org/grants-and-funding/soroban-audit-bank

Stellar Development Foundation. (2026). *Stellar SCF 7.0: Grants & Funding Tracks for Web3 Builders*.  
https://stellar.org/blog/ecosystem/introducing-scf-v7

Stellar Development Foundation. (s. f.). *Build Awards*.  
https://communityfund.stellar.org/awards
