# Proyecto Final Ingeniería de Software
Equipo: Parchis  
Integrantes: Aldo Soria, Regina Rodríguez y Juan Manuel Ambriz  
Repositorio para el proyecto final de Ingenieria de Software  
## Arquitectura del Proyecto
La arquitectura seleccionada para este proyecto es basada en eventos (event-driven), ya que es la más adecuada para un chatbot desarrollado en Landbot.io que guía a nuevos estudiantes del ITAM a través de WhatsApp. Esta decisión se fundamenta en la reactividad de los chatbots, donde cada interacción del usuario genera un evento que desencadena procesos específicos. La arquitectura basada en eventos permite manejar estas interacciones de manera eficiente, escalable y modular, aprovechando las capacidades de Landbot.io como núcleo.
## Justificación de la Arquitectura
Elegimos la arquitectura basada en eventos por las siguientes razones:
1.	**Compatibilidad con Landbot.io:** Landbot.io utiliza webhooks para generar eventos cuando el usuario hace una acción, facilitando la integración con otros servicios.
2.	**Independencia:** Los componentes del sistema funcionan de manera independiente, reaccionando únicamente a eventos relevantes.
3.	**Escalabilidad:** Permite manejar múltiples interacciones concurrentes, lo cual es ideal si el chatbot debe responder a una gran cantidad de usuarios al mismo tiempo.
4.	**Flexibilidad:** Facilita que se añadan nuevas funcionalidades, sin alterar los servicios existentes.
