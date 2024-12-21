# Proyecto Final Ingeniería de Software
Equipo: Parchis  
Integrantes: Aldo Soria, Regina Rodríguez y Juan Manuel Ambriz  
Repositorio para el proyecto final de Ingenieria de Software  

## [Software Requirements](Requerimientos.pdf) 
## Casos de uso: ([https://github.com/ReginaRodriguez23-08/parchisProyectoFinal/tree/72c7fefe3daafe6f410c90495f27a739f3812657/Casos%20de%20Uso])
## [Plan de calidad](PlandeCalidad.pdf) 

## Arquitectura
La arquitectura seleccionada para este proyecto es basada en eventos (event-driven), ya que es la más adecuada para un chatbot desarrollado en Landbot.io que guía a nuevos estudiantes del ITAM a través de WhatsApp. Esta decisión se fundamenta en la reactividad de los chatbots, donde cada interacción del usuario genera un evento que desencadena procesos específicos. La arquitectura basada en eventos permite manejar estas interacciones de manera eficiente, escalable y modular, aprovechando las capacidades de Landbot.io como núcleo.
## Justificación de la Arquitectura
Elegimos la arquitectura basada en eventos por las siguientes razones:
1.	**Compatibilidad con Landbot.io:** Landbot.io utiliza webhooks para generar eventos cuando el usuario hace una acción, facilitando la integración con otros servicios.
2.	**Independencia:** Los componentes del sistema funcionan de manera independiente, reaccionando únicamente a eventos relevantes.
3.	**Escalabilidad:** Permite manejar múltiples interacciones concurrentes, lo cual es ideal si el chatbot debe responder a una gran cantidad de usuarios al mismo tiempo.
4.	**Flexibilidad:** Facilita que se añadan nuevas funcionalidades, sin alterar los servicios existentes.  

## Metodología 
La metodología seleccionada para el desarrollo de este proyecto es Agile, debido a su enfoque iterativo y flexible, ideal para proyectos como este, ya que en los que los requisitos pueden cambiar con base en el feedback de los usuarios. Agile permite dividir el trabajo en sprints, lo que facilita la mejora progresiva del sistema. Esto es especialmente relevante para nuestro chatbot en WhatsApp, ya que las funcionalidades pueden evolucionar para adaptarse mejor a las necesidades de los nuevos estudiantes del ITAM.
## Justificación de la Metodología
Elegimos Agile por las siguientes razones:
1.	Iteración y mejora continua: El desarrollo en sprints permite implementar funcionalidades básicas desde el inicio (como los flujos principales de conversación en Landbot.io) y mejorarlas en versiones posteriores.
2.	Flexibilidad: La metodología se adapta fácilmente a cambios en los requisitos, como nuevos flujos de conversación o la integración de tecnologías adicionales.
3.	Entrega temprana funcional: Las funcionalidades esenciales del chatbot pueden ponerse en funcionamiento rápidamente, mientras se sigue trabajando en optimizaciones y mejoras.

## Código del proyecto: ([parchisProyectoFinal/Código proyecto/](https://github.com/ReginaRodriguez23-08/parchisProyectoFinal/tree/a939e3b63fbf73088ba64f3174e7ab8366cdc408/C%C3%B3digo%20proyecto))

## [Documentación para replicar](DocumentaciónParaReplicar.docx)

## Propuesta Económica

## [Presentación](Presentacion.pdf)
