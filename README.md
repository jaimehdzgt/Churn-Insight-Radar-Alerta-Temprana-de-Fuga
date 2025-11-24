# Churn-Insight-Radar-Alerta-Temprana-de-Fuga - Resume el riesgo de churn y prioriza acciones comerciales.


## 🎯 Problema de negocio y solución – Saturn Telecom

**Problema de negocio**  
Saturn Telecom observaba mes a mes una pérdida constante de clientes en sus servicios de telefonía, pero solo veía el churn como un porcentaje global al cierre del periodo. 
No existía visibilidad clara de **qué clientes estaban en mayor riesgo**, ni de **qué comportamientos o características los diferenciaban**. 
Esto provocaba que las acciones de retención fueran generales, poco focalizadas y principalmente reactivas: se actuaba cuando el cliente ya había cancelado.

**Cómo se resolvió**  
Para atacar este problema se desarrolló una solución de **scoring de churn** basada en Data Science. A partir del histórico de clientes de Saturn Telecom (uso del servicio, antigüedad, historial de pago, comportamiento reciente, etc.) se construyó un dataset etiquetando quiénes cancelaron y quiénes permanecieron activos. Con esta información se:

- Prepararon y depuraron los datos para asegurar su calidad.
- Diseñaron variables que capturan patrones de comportamiento relevantes.
- Entrenó un modelo de clasificación que asigna a cada cliente un **puntaje de probabilidad de churn**.
- Integraron los resultados en un tablero donde negocio puede **segmentar y priorizar clientes por nivel de riesgo**, además de explorar los factores que más influyen en la cancelación.

<img src="assets/Churn_Insight_Slides.gif" alt="Demo del dashboard" width="100%">

**Resultado**  
Con este enfoque, Saturn Telecom pasa de reaccionar al churn a **anticiparlo**. El área de negocio puede ahora:

- Identificar con rapidez a los clientes en “zona roja” y priorizar acciones sobre ellos.
- Dirigir campañas, ofertas y contactos personalizados donde tienen mayor impacto.
- Entender mejor qué variables se relacionan con el abandono y utilizarlas para mejorar producto, servicio y experiencia del cliente.

En resumen, el modelo de churn scoring se convierte en una herramienta práctica para **reducir la pérdida de clientes, optimizar el presupuesto de retención y tomar decisiones más informadas basadas en datos**.



