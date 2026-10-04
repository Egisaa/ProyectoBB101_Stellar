# Problem Brief

## Decisión del problema

### Problema elegido

> La alta barrera de entrada económica impide que la mayoría de las personas invierta en bienes raíces generadores de renta.

### Por qué elegimos este

> Este problema fue seleccionado porque ataca una necesidad real y cotidiana de inclusión financiera en América Latina. A diferencia de otras propuestas más especulativas o de nicho, el acceso a la vivienda y a la renta inmobiliaria es una aspiración universal de protección contra la inflación. Además, permite un caso de uso muy claro donde la fragmentación digital aporta un valor tangible que el sistema financiero tradicional no logra ofrecer de manera eficiente y económica.

### Propuestas descartadas

> Trazabilidad de cadenas de suministro agrícolas : Descartado porque el mercado objetivo local es complejo de abordar en las primeras etapas y requiere la adopción de múltiples actores rurales reacios a la tecnología.

Gestión descentralizada de historiales médicos : Descartado debido a las altas barreras regulatorias de privacidad de datos (leyes de salud) y la resistencia institucional de clínicas y hospitales.

### Cómo tomamos la decisión

> Evaluando la viabilidad técnica, la accesibilidad de las fuentes de información y el impacto real que el proyecto podría generar en el corto plazo para los usuarios cotidianos

---

## Problem Brief

### Encabezado

> InmoToken Democratización y liquidez fraccionada para la inversión en bienes raíces generadores de renta.

### Equipo y roles

> Emily - [https://github.com/Egisaa] – Líder de Producto y Arquitectura

### Problema y evidencia

> La alta barrera de entrada económica impide que los pequeños ahorradores inviertan en bienes raíces generadores de renta. Este obstáculo se experimenta de forma constante por cualquier persona que reciba ingresos mensuales fijos y busque proteger su dinero de la inflación a través de la propiedad raíz, pero que carece de los ahorros necesarios para adquirir un inmueble o una cuota inicial tradicional.

La evidencia de este problema es directa y cotidiana: los precios promedio de la finca raíz en las principales ciudades de la región superan por mucho la capacidad de ahorro mensual de un ciudadano promedio, cuyos ahorros suelen quedar confinados en cuentas bancarias tradicionales de bajo rendimiento o en fondos de inversión con comisiones elevadas y mínimos de entrada prohibitivos que exigen miles de dólares.

### Usuario y actores

> El principal afectado es el pequeño inversor urbano, una persona natural con capacidad de ahorro moderada que busca generar ingresos pasivos y diversificar su patrimonio, pero que hoy solo puede acceder a cuentas de ahorros tradicionales con rentabilidades reales negativas frente a la inflación.

Los demás actores que intervienen en el flujo actual son:

El desarrollador o propietario del inmueble: Busca liquidez rápida o capital para nuevos proyectos.

Las fiduciarias o bancos tradicionales: Actúan como intermediarios obligatorios para custodiar los fondos y administrar los contratos, cobrando altas comisiones administrativas.

Las notarías y oficinas de registro: Validan legalmente la transferencia de los títulos de propiedad de forma centralizada y presencial.

### Flujo actual de valor

> El propietario o constructor emite un proyecto inmobiliario y contrata a una fiduciaria para estructurar un fideicomiso.

La fiduciaria publica el proyecto y exige a los inversores cumplir con montos mínimos de entrada elevados (generalmente superiores al 20% del valor total de una unidad o participaciones corporativas cerradas).

El inversor transfiere el dinero a través del sistema bancario tradicional a la cuenta de la fiduciaria.

Tras un proceso burocrático de verificación de identidad (KYC/AML) y firma de contratos físicos o notariales, se formaliza la participación.

El inmueble genera rentas mensuales que la fiduciaria recauda, deduciendo costos administrativos y comisiones de gestión antes de transferir los remanentes al inversor.

Si el inversor desea recuperar su dinero antes de tiempo, debe enfrentar un mercado secundario rígido, lento y costoso, altamente dependiente de intermediarios.

### Fricciones identificadas

> Altos costos de intermediación: Las comisiones cobradas por fiduciarias y administradores reducen significativamente la rentabilidad neta del pequeño inversor (Ocurre en el paso 5; afecta al inversor).

Baja liquidez y tiempos de salida prolongados: Vender una fracción de un inmueble tradicional toma meses o años, debido a la ausencia de un mercado secundario ágil (Ocurre en el paso 6; afecta al inversor).

Burocracia y fricción legal: La necesidad de trámites notariales presenciales y validaciones manuales desacelera la entrada de capital y encarece la operación (Ocurre en el paso 4; afecta a todos los actores).

### Oportunidad e hipótesis

> La oportunidad priorizada es la eliminación de las altas barreras económicas de entrada y la reducción drástica de las fricciones de liquidez mediante la fraccionización digital de los títulos de propiedad.

Hipótesis inicial: Si digitalizamos los derechos económicos de un inmueble generador de renta en unidades de menor valor accesible, entonces el pequeño inversor podrá comprar y vender participaciones de forma inmediata sin depender de fiduciarias tradicionales, incrementando su acceso a rentabilidad inmobiliaria y disponibilidad de liquidez.

### Criterio de pertinencia

> Este caso requiere un registro distribuido y no una base de datos tradicional centralizada porque involucra partes que no confían plenamente entre sí (inversores minoristas dispersos, el administrador del inmueble y los emisores originales) y que necesitan compartir de forma transparente e inalterable un mismo registro de propiedad y distribución de dividendos.

Si se utilizara una base de datos tradicional administrada por una sola empresa, los usuarios estarían expuestos a la manipulación unilateral de datos, falta de transparencia en el recaudo de rentas o riesgo de contraparte si el operador central quiebra o decide modificar las reglas de reparto. La tecnología de registro distribuido elimina la necesidad de depositar toda la confianza en un único intermediario centralizado.

### Supuestos y riesgos

> Supuesto 1: Existirá un marco regulatorio local o mecanismos de estructuración legal híbridos que reconozcan el vínculo legal entre el token digital y los derechos económicos del inmueble físico.

Supuesto 2: Los usuarios minoristas adoptarán la tecnología de billeteras digitales con la suficiente facilidad para gestionar sus participaciones de manera autónoma.

Riesgo principal que invalidaría la hipótesis: Un cambio normativo estricto que prohíba la emisión de representaciones digitales de activos inmobiliarios sin licencias bancarias masivas e inalcanzables para una plataforma en etapa temprana.