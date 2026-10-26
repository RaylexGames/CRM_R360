# Control de Servicios R360

PROPUESTA PARA ERIC FABIÁN MUÑOZ · SOCIO DIRECTOR

Documento para revisión funcional y comercial · Revisión de cierre 5. Base comercial: cotización del 17 de octubre de 2026.

## 01 · Brief del proyecto

R360 contará con una plataforma digital propia para centralizar la administración de servicios, clientes, expedientes, responsables, documentos, actividades, seguimiento y control operativo. La solución será una aplicación web progresiva (PWA), instalable y accesible desde computadoras y dispositivos móviles, con arquitectura modular y multicliente: cada cuenta dispondrá de información segregada y configuraciones particulares sin modificar el núcleo común.

R360 controlará sus usuarios, permisos, información, servicios y operación cotidiana. La plataforma incorporará captura móvil, gestión documental, seguimiento de tareas, trazabilidad, alertas y mecanismos técnicos de seguridad, respaldo y recuperación. Su arquitectura permitirá integrar nuevos canales, servicios y capacidades de inteligencia artificial en etapas futuras, sin que las funciones de IA formen parte del alcance operativo de esta entrega.

En los primeros 45 días naturales, contados según las condiciones de arranque, se habilitarán Asistencia Legal Automovilística y Gestoría Vehicular. Al finalizar el segundo mes la plataforma y esos dos módulos deberán operar en producción con la infraestructura, API, seguridad, respaldos, restauración, monitoreo y capacidad inicial comprobados. El resto del portafolio acordado se incorporará durante los meses 3 a 6.

## 02 · Inversión del desarrollo

| Desarrollo completo | IVA (16%) | Total MXN |
| --- | --- | --- |
| $200,000 | $32,000 | $232,000 |

## 03 · Calendario de trabajo y pagos

| Mes | Entrega y resultado | Sin IVA | Con IVA |
| --- | --- | --- | --- |
| 1 | Definición de reglas y recorridos en días 1–15; arquitectura modular y multicliente; diseño funcional, PWA, API base; usuarios y permisos por perfil; preparación de infraestructura y controles operativos. | $35,000 | $40,600 |
| 2 | Al día 45, Asistencia Legal Automovilística y Gestoría Vehicular completas y utilizables. Al cierre del mes 2: operación en producción validada, API funcional y documentada para ambos servicios, seguridad y segregación por cliente, fotos a PDF, alertas y tareas, respaldos con restauración probada, monitoreo y prueba de capacidad para la carga inicial aprobada. | $35,000 | $40,600 |
| 3 | Módulos de Defensa y Recuperación Civil, Subrogación y Mediación; modalidades de autos, vida y gastos médicos y atención relacionada con CONAMED y CONDUSEF. Ampliación de API y recorridos por cuenta. | $35,000 | $40,600 |
| 4 | Control económico, administración, supervisión y calidad; valoraciones del servicio dentro de la plataforma, consultas y reportes por permisos; reglas de completitud y salud de expedientes. | $35,000 | $40,600 |
| 5 | Apoderado Legal, Robo, Localización y Recuperación de Vehículo, Cobranza Judicial y CONDUSEF; Asesoría Telefónica, Gestoría Administrativa, flotas, Concierge y VIP, conforme a recorridos aprobados. | $35,000 | $40,600 |
| 6 | Integraciones externas acordadas que permanezcan dentro del alcance, reportes ejecutivos, validación integral de los módulos agregados, pruebas de regresión, documentación, capacitación y entrega final de código y derechos al liquidar. | $25,000 | $29,000 |
| TOTAL | Desarrollo completo | $200,000 | $232,000 |

Hitos: los 45 días y los seis meses se computan desde el primer pago, las definiciones iniciales aprobadas y los accesos necesarios, registrados en el acta de arranque. La operación de los módulos iniciales no equivale a la entrega de todo el portafolio.

## 04 · Coordinación del proyecto

R360 designará un responsable de decisiones y validación. Cabina, jurídico y gestoría participarán en la revisión de recorridos y entregables correspondientes. Durante los primeros 15 días se aprobarán reglas, catálogos, criterios de aceptación y recorridos; los avances se revisarán semanalmente. Las decisiones, observaciones, pendientes, responsables y fechas se documentarán por escrito. Las modificaciones de alcance requerirán análisis de impacto y autorización, conforme a las condiciones comerciales pactadas.

## 05 · Alcance funcional y operativo

### PWA, usuarios y autonomía

Aplicación instalable, con captura por perfil y pasos, confirmación de guardado, prevención de duplicados por reintento y aviso ante modificaciones simultáneas. R360 administrará cuentas, usuarios y permisos. Campos, formatos, coberturas y reglas podrán configurarse por cliente dentro de las posibilidades acordadas. La aplicación requiere conexión a internet; se validarán dispositivos, tamaños y formatos soportados.

### Expedientes, documentos y seguimiento

El expediente reunirá personas, vehículos, trámites, actuaciones, documentos, importes, fechas, tareas, historial y responsables. Contará con búsqueda, estados validados, trazabilidad, permisos documentales y exportaciones PDF/CSV. Las fotografías podrán ordenarse, previsualizarse y convertirse en PDF. Los recordatorios a responsables e involucrados autorizados se gestionarán desde la PWA y el servidor, con bandeja de avisos y notificaciones push cuando el dispositivo y sus permisos lo permitan.

Asistencia Legal Automovilística seguirá recepción, asignación, monitoreo y entrega a coordinación. Para detenidos, se contemplan revisiones cada cuatro horas y, después de 24 horas, cada ocho horas o según la instrucción registrada. Se medirán por separado el objetivo condicionado de arribo de 60 minutos y la activación crítica en menos de 48 horas. El cierre requerirá los soportes y vistos buenos exigibles.

### Salud y revisión de expedientes

Se implementarán controles basados en reglas, sin inteligencia artificial, para conocer la integridad del expediente según campos, documentos y autorizaciones exigibles por tipo de servicio y cliente. Se distinguirán completitud, validación y cumplimiento de plazos; faltantes críticos podrán generar alertas o impedir el cierre. La matriz, las ponderaciones, las excepciones y los destinatarios de avisos se concretarán en la definición funcional, sin introducir obligaciones ajenas al alcance pactado.

### API, importación, exportación y comunicaciones

La API permitirá consultar, registrar y actualizar información autorizada de los servicios habilitados, con autenticación, versionado, controles de duplicados, documentación, errores y reintentos. Se incluyen exportaciones PDF/CSV y equivalencias de datos para las conexiones acordadas. La importación y exportación por cliente, individual y por lotes conforme al recorrido aprobado, están incluidas en el precio. Se documentarán durante el proyecto los sistemas y recorridos objeto de integración, sin presumir conectores futuros ilimitados. Se definirán por conexión los campos, equivalencias, formatos JSON, CSV o Excel según el sistema externo, volúmenes, permisos, validación, duplicados, actualización, errores y pruebas de aceptación. La especificación de las funciones incluidas no genera por sí misma un cobro adicional. Las conexiones requieren documentación, accesos y autorizaciones válidas del tercero; sus dependencias y eventuales reprogramaciones deberán acreditarse y acordarse por escrito, sin liberación automática de obligaciones.

Los avisos, recordatorios y encuestas de satisfacción se centrarán en la PWA. Las integraciones incluidas se desarrollarán conforme al inventario aprobado. Las integraciones nuevas que excedan lo acordado se evaluarán mediante control de cambios. No se incorporan funciones de IA en esta fase.

## 06 · Infraestructura y presupuesto de operación

R360 contratará los servicios externos en sus propias cuentas y mantendrá control sobre la operación y los datos. La arquitectura concreta, región, capacidad, mecanismos de alta disponibilidad y servicios administrados se seleccionarán en la definición técnica. Los costos siguientes son referencias sujetas a dimensionamiento y aprobación conforme a la arquitectura y capacidad acordadas.

| Concepto | Referencia mensual MXN | Condición |
| --- | --- | --- |
| AWS: aplicación, datos, archivos, red, respaldos, monitoreo y pruebas | $4,000–$6,500 | Dimensionar con arquitectura y recuperación del mes 2. |
| Dominio | $50–$100 | Revisar proveedor y contratación. |

La estimación original se basó en 30–50 usuarios, hasta 10 simultáneos, 100 GB de archivos y una referencia de AWS Virginia y dólar presupuestal de $20 MXN. Las pruebas de capacidad y recuperación para la carga inicial aprobada deberán estar completadas al finalizar el mes 2; el mes 6 incluirá pruebas integrales de ampliaciones y regresión.

## 07 · Entregables, aceptación y transferencia

Se entregarán diseños editables, componentes, accesos, configuraciones, diccionario de datos, documentación de API, código y guías de despliegue, respaldo y recuperación. Se contemplan entornos separados para pruebas y producción, manual y dos capacitaciones de dos horas. Cada entrega se revisará mediante casos de prueba acordados: R360 dispondrá de cinco días hábiles para aceptar o señalar diferencias; el silencio no constituye aceptación.

La aceptación del mes 2 comprobará recorridos de ambos servicios, instalación y uso de la PWA, documentos y fotos a PDF, permisos y separación entre clientes, funcionamiento de API, monitoreo, restauración de respaldo y carga inicial acordada, sin fallas críticas abiertas. Al cierre del proyecto se entregará el inventario de integraciones, se verificarán las ampliaciones y se formalizarán la entrega integral y la cesión conforme a las condiciones comerciales.

## 08 · Garantía, soporte y mantenimiento

Cada entrega aceptada tendrá una garantía de 60 días naturales; la integración final contará con su propio periodo. Los defectos comunicados durante la garantía se atenderán hasta su cierre aunque esta haya vencido. Las funciones nuevas y los cambios ajenos al desarrollo se evaluarán aparte. El soporte posterior es opcional y sus condiciones específicas deberán formalizarse antes de contratarse.

| Concepto | Referencia / condición | Situación |
| --- | --- | --- |
| Garantía | 60 días naturales por entrega aceptada, sin cargo adicional | Se conserva. |
| Mantenimiento posterior | $5,000–$10,000 MXN al mes + IVA | Rango original; cobertura por acordar. |
| Incidente crítico | Primera respuesta orientativa original: 4 horas hábiles | R360 solicita tiempos menores: SLA pendiente de acordar. |
| Incidente alto | Primera respuesta original: 8 horas hábiles | Revisión en SLA. |
| Incidente normal | Primera respuesta original: 2 días hábiles | Revisión en SLA. |
| Incumplimientos y escalamiento | Consecuencias, avisos, créditos o remedios contractuales | Pendiente de negociación; no se presumen aprobados. |

La operación 24/7 de R360 no implica por sí sola disponibilidad técnica 24/7. Se acordarán horarios, contacto de emergencia, severidades, tiempos de primera respuesta, objetivos de recuperación, escalamiento y medidas ante incumplimiento. Las respuestas y las recuperaciones son métricas distintas: no se garantiza un plazo de resolución definitivo sin validación técnica y contractual.

Se prevé monitoreo de disponibilidad de PWA, API, base de datos, errores, capacidad y respaldos; alertas al soporte y un procedimiento documentado de diagnóstico, contención, recuperación, verificación y reporte posterior. R360 conservará la propiedad y control de las cuentas; el acceso técnico será individual, autorizado, auditable y limitado a lo necesario.

## 09 · Condiciones comerciales

Precio y pago: $200,000 MXN más IVA de $32,000, total $232,000. Meses 1 a 5: $35,000 más IVA ($40,600) al inicio de cada periodo. Mes 6: $25,000 más IVA ($29,000), contra revisión, entrega y aceptación final. Sin incrementos automáticos.

Inicio y alcance: los seis meses y 45 días naturales se contarán desde el primer pago, la aprobación de funciones iniciales y los accesos necesarios, asentados en el acta de arranque. Se confirmará la capacidad de entrega antes de contratar. Alcance detallado y criterios de aceptación se formalizarán por escrito. Cualquier cambio requerirá

impacto y acuerdo escrito, sin aumentos automáticos. Un retraso externo no libera al prestador de sus obligaciones.

Terceros y operación: alojamiento, base gestionada, dominio, archivos y demás consumos externos aprobados se pagan aparte. R360 aporta atención profesional, contenidos y gastos jurídicos. El CRM registra pagos, documentos y actuaciones; no transfiere dinero, emite CFDI ni garantiza resultados judiciales. Los adaptadores requieren APIs y autorizaciones válidas.

Datos y confidencialidad: R360 conserva el control y acceso a la información operativa, respetando derechos de los titulares. Se acordarán roles de tratamiento, avisos, bases legales, proveedores y transferencias. El prestador actuará bajo instrucciones autorizadas, con confidencialidad, seguridad, aviso sin dilación de incidentes y devolución o supresión conforme a conservación legal.

Propiedad y cierre: al liquidar se entregará la plataforma y se cederán por escrito a Eric o a la entidad que designe los derechos patrimoniales sobre código a medida, diseños y documentación. Podrá operar y mantener la plataforma con otro proveedor; las bibliotecas de terceros conservarán sus licencias. Una terminación anticipada liquidará avances verificables y anticipos no devengados, y acordará entrega y derechos de resultados pagados. El contrato precisará partes, RFC, facturación, notificaciones, subsanación, responsabilidades y jurisdicción. Vigencia de la propuesta original: 31 de octubre de 2026. No es CFDI. NOTA DE CONTROL DE CAMBIOS: esta revisión reorganiza apartados y recoge decisiones funcionales posteriores a la junta. No modifica el precio ni el esquema de pagos. Los SLA, penalizaciones y dimensionamiento de infraestructura permanecen sujetos a validación. La importación y exportación por cliente están incluidas en el precio; sus formatos, volúmenes y especificaciones se definirán por escrito durante el proyecto.
