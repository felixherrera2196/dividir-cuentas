# Cuestionario para definir requerimientos de la aplicación "Dividir Cuentas"

## 1. Contexto y alcance general
1. ¿Qué escenarios de uso principales esperan cubrir con la aplicación (viajes, salidas ocasionales, convivencia diaria, etc.)?
2. ¿Cuál es el número estimado de participantes por grupo y cuántos grupos diferentes podrían gestionar simultáneamente?
3. ¿Desean que la aplicación funcione únicamente para un grupo específico por evento o que permita manejar múltiples eventos y grupos activos a la vez?
4. ¿Existen restricciones de presupuesto o plazos que debamos considerar para el desarrollo inicial?

## 2. Usuarios y roles
1. ¿Los usuarios necesitarán registrarse con cuentas individuales o bastará con enlaces de acceso compartidos?
2. ¿Habrá diferentes roles (administrador del grupo, miembros regulares) con permisos diferenciados?
3. ¿Requieren autenticación social (Google, Facebook, etc.) o solo correo electrónico y contraseña?
4. ¿Necesitan soporte para invitar a nuevos participantes mediante correo, enlace o código?

## 3. Gestión de grupos y eventos
1. ¿Cada grupo corresponde a un único evento o un grupo puede contener múltiples eventos/salidas con sus propios gastos?
2. ¿Los usuarios podrán duplicar o archivar grupos/eventos para reutilizar información anterior?
3. ¿Se necesita controlar el estado del evento (en curso, cerrado, liquidado) y quién puede cerrarlo?
4. ¿Desean establecer límites en el número de gastos o participantes por grupo/evento?

## 4. Registro de gastos
1. ¿Qué información mínima debe registrarse para cada gasto (concepto, monto, pagador, fecha, categoría, notas, comprobantes)?
2. ¿Los gastos pueden dividirse solo en partes iguales o se requiere soportar divisiones proporcionales/personalizadas (por persona, por porcentaje, por unidades)?
3. ¿Se deben soportar múltiples monedas y, de ser así, cómo manejarán las conversiones?
4. ¿Desean permitir adjuntar comprobantes (fotos, PDFs) a cada gasto?
5. ¿Hay validaciones específicas (por ejemplo, evitar montos negativos, montos máximos, categorías obligatorias)?

## 5. Participación y aportaciones
1. ¿Todos los participantes contribuyen con el mismo peso en los cálculos o habrá participantes opcionales (solo invitados, niños, etc.)?
2. ¿Se deben considerar ajustes individuales (por ejemplo, alguien que no consume cierta categoría y no debe pagarla)?
3. ¿Cómo manejar gastos compartidos parcialmente entre subgrupos de participantes?
4. ¿Necesitan registrar pagos directos entre participantes (settlements) dentro de la plataforma y reflejarlos en el balance?

## 6. Cálculo y conciliación
1. ¿Desean ver resúmenes por persona, por categoría y por evento, además de la división general?
2. ¿Cómo debe presentarse la instrucción de pagos finales (lista de transferencias sugeridas, flujo óptimo de pagos, exportable)?
3. ¿Se necesita soporte para diferentes métodos de conciliación (mínimo número de transacciones, pagos circulares, etc.)?
4. ¿La aplicación debe recalcular saldos automáticamente ante cada gasto nuevo o cierre manual del evento?
5. ¿Requieren un historial de ajustes o versiones anteriores de los balances?

## 7. Notificaciones y comunicación
1. ¿Qué tipo de notificaciones desean (correo, push, SMS) y en qué momentos (nuevo gasto, cierre de evento, recordatorios de pago)?
2. ¿Desean permitir comentarios o chat entre los miembros del grupo sobre los gastos?
3. ¿Necesitan integraciones con mensajería externa (WhatsApp, Slack) para compartir resúmenes o enlaces?

## 8. Experiencia de usuario e interfaz
1. ¿Existen preferencias de idioma(s) y formatos de moneda/fecha que debamos soportar?
2. ¿La aplicación debe ser responsive para móviles, tabletas y escritorio?
3. ¿Requieren una guía o tutorial inicial para usuarios nuevos?
4. ¿Hay lineamientos de marca (colores, tipografías, logotipo) que debamos seguir?

## 9. Reportes y exportaciones
1. ¿Desean exportar resúmenes o balances en formatos específicos (PDF, Excel, CSV)?
2. ¿Se deben generar informes históricos por rango de fechas o por evento?
3. ¿Necesitan integraciones con herramientas externas de contabilidad o finanzas?

## 10. Seguridad y privacidad
1. ¿Existen requisitos de cumplimiento (por ejemplo, GDPR, Ley de Protección de Datos local) que debamos considerar?
2. ¿Se requiere cifrado de datos en reposo y en tránsito?
3. ¿Cómo deben gestionarse las copias de seguridad y la recuperación ante desastres?
4. ¿Qué políticas de retención o eliminación de datos deben aplicarse tras cerrar un evento o eliminar un usuario?

## 11. Administración y soporte
1. ¿Habrá un panel administrativo para monitorear actividad, gestionar usuarios y resolver incidencias?
2. ¿Qué métricas desean ver a nivel administrativo (número de grupos activos, gastos totales, usuarios activos)?
3. ¿Qué canal de soporte ofrecerán a los usuarios (FAQ, tickets, chat en vivo) y cómo se integrará con la aplicación?

## 12. Requerimientos técnicos y despliegue
1. ¿Tienen preferencias tecnológicas para el frontend, backend o base de datos?
2. ¿Dónde se desplegará la aplicación (infraestructura propia, nube específica)?
3. ¿Se necesitan entornos separados (desarrollo, pruebas, producción) y pipelines de despliegue automatizados?
4. ¿Hay integraciones planeadas con servicios existentes del cliente (sistemas de autenticación, ERPs, pasarelas de pago)?

## 13. Futuras mejoras y escalabilidad
1. ¿Qué funcionalidades adicionales visualizan a mediano plazo (por ejemplo, presupuestos, préstamos, estadísticas avanzadas)?
2. ¿Desean soporte para extensiones o API pública para que terceros integren la aplicación?
3. ¿Cómo esperan que crezca la base de usuarios y qué nivel de escalabilidad debe soportar la plataforma?

## 14. Éxito y métricas
1. ¿Cómo medirán el éxito del proyecto (adopción, reducción de disputas, satisfacción de usuarios)?
2. ¿Qué indicadores clave de rendimiento (KPIs) desean monitorear desde el lanzamiento?

