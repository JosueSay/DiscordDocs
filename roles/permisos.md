# Explicación de los permisos 🛡️

## 📜 Permisos Generales del Servidor

| Permiso                       | Qué permite                                                                             | Qué no permite                                                           | Explicación simple                                       |
| ----------------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | -------------------------------------------------------- |
| **Ver canales**               | Ver todos los canales visibles para el rol.                                             | No da acceso a canales privados sin permiso específico.                  | Es como tener llaves para entrar a las salas visibles.   |
| **Gestionar canales**         | Crear, editar o eliminar canales de texto/voz.                                          | No afecta permisos de roles o categorías.                                | Puedes construir o quitar “habitaciones” en el servidor. |
| **Gestionar roles**           | Crear, editar y eliminar roles de menor rango, cambiar permisos de canales que manejes. | No puedes cambiar roles más altos que el tuyo.                           | Dar y quitar “rangos” y sus permisos.                    |
| **Crear expresiones**         | Subir stickers, sonidos y emojis personalizados.                                        | No puedes editar los de otros sin el permiso de “Gestionar expresiones”. | Agregar tus propios emojis/stickers al servidor.         |
| **Gestionar expresiones**     | Editar o borrar stickers, sonidos y emojis personalizados.                              | No crea expresiones nuevas si no tienes “Crear expresiones”.             | Modificar o borrar emojis existentes.                    |
| **Ver registro de auditoría** | Ver cambios y acciones hechas en el servidor (quién borró, editó, movió cosas).         | No puedes revertir los cambios.                                          | Revisar el “historial” de acciones del servidor.         |
| **Gestionar webhooks**        | Crear, editar o eliminar webhooks que publiquen en el servidor.                         | No afecta a bots o integraciones que no usen webhooks.                   | Conectar apps externas para enviar mensajes automáticos. |
| **Gestionar servidor**        | Cambiar nombre, región, invitaciones, agregar apps, configurar AutoMod.                 | No incluye permisos de administrador total.                              | Ajustar opciones globales del servidor.                  |

## 📜 Permisos de Membresía

| Permiso                                   | Qué permite                                               | Qué no permite                                              | Explicación simple                              |
| ----------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------- |
| **Crear invitación**                      | Generar enlaces para invitar gente.                       | No controla el acceso a canales privados.                   | Dar llaves para que otros entren al servidor.   |
| **Cambiar apodo**                         | Cambiar tu propio apodo en ese servidor.                  | No cambia tu nombre global.                                 | Cambiar cómo te ven en ese servidor.            |
| **Gestionar apodos**                      | Cambiar apodos de otros miembros.                         | No expulsa ni cambia roles.                                 | Editar cómo se llaman otros.                    |
| **Expulsar, aprobar o rechazar miembros** | Sacar miembros o aceptar/denegar solicitudes.             | No prohíbe permanentemente (para eso es “Banear miembros”). | Poner a alguien “afuera” del servidor.          |
| **Banear miembros**                       | Bloquear y borrar mensajes de un miembro permanentemente. | No puede banear a miembros con roles más altos.             | Expulsar para siempre.                          |
| **Aislar temporalmente a miembros**       | Evitar que un usuario interactúe (mute global temporal).  | No elimina mensajes ni roles.                               | Poner en “modo silencio” a alguien por un rato. |

## 📜 Permisos del Canal de Texto

| Permiso                                    | Qué permite                                          | Qué no permite                                    | Explicación simple                         |
| ------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------- | ------------------------------------------ |
| **Enviar mensajes y crear publicaciones**  | Escribir en canales y foros.                         | No permite en canales bloqueados.                 | Hablar en el chat.                         |
| **Enviar mensajes en hilos/publicaciones** | Escribir en hilos y temas de foro.                   | No crea hilos si no tienes permiso de crearlos.   | Participar en conversaciones separadas.    |
| **Crear hilos públicos**                   | Abrir hilos visibles para todos.                     | No crea hilos privados.                           | Iniciar subtemas abiertos.                 |
| **Crear hilos privados**                   | Abrir hilos solo por invitación.                     | No crea hilos públicos.                           | Iniciar chats secretos dentro de un canal. |
| **Insertar enlaces**                       | Mostrar vista previa de links.                       | No impide mandar links simples sin vista previa.  | Pegar un link y que se vea la miniatura.   |
| **Adjuntar archivos**                      | Subir imágenes, videos y otros.                      | No afecta texto.                                  | Enviar fotos o documentos.                 |
| **Añadir reacciones**                      | Poner emojis a mensajes.                             | No quita reacciones ajenas.                       | Reaccionar con caritas.                    |
| **Usar emojis externos**                   | Usar emojis de otros servidores (si tienes Nitro).   | No crea emojis nuevos.                            | Usar emojis que no son de este servidor.   |
| **Usar stickers externos**                 | Usar stickers de otros servidores (si tienes Nitro). | No crea stickers nuevos.                          | Usar stickers externos.                    |
| **Mencionar @everyone/@here/roles**        | Mencionar a todos, online o un rol.                  | No menciona roles sin permiso específico.         | Llamar la atención de todos.               |
| **Gestionar mensajes**                     | Borrar o fijar mensajes de otros.                    | No modifica roles o permisos.                     | Ser moderador del chat.                    |
| **Gestionar hilos/publicaciones**          | Cerrar, borrar, renombrar hilos.                     | No crea nuevos hilos.                             | Administrar conversaciones abiertas.       |
| **Leer historial de mensajes**             | Ver mensajes anteriores en un canal.                 | Sin esto, solo ves los nuevos desde que entraste. | Poder “scrollear” arriba.                  |
| **Enviar mensajes de texto a voz**         | Usar /tts para que se lea en voz.                    | No afecta mensajes normales.                      | Que el bot lea tu mensaje en voz.          |
| **Enviar mensajes de voz**                 | Enviar clips de voz en canales de texto.             | No es lo mismo que hablar en voz.                 | Mandar audios como en WhatsApp.            |
| **Crear encuestas**                        | Hacer encuestas interactivas.                        | No obliga a responder.                            | Hacer votaciones rápidas.                  |

## 📜 Permisos del Canal de Voz

| Permiso                               | Qué permite                                     | Qué no permite                               | Explicación simple                       |
| ------------------------------------- | ----------------------------------------------- | -------------------------------------------- | ---------------------------------------- |
| **Conectar**                          | Entrar a canales de voz.                        | No garantiza poder hablar.                   | Escuchar y estar presente.               |
| **Hablar**                            | Usar micrófono.                                 | No permite compartir pantalla.               | Poder hablar en voz.                     |
| **Vídeo**                             | Activar cámara o compartir pantalla.            | No afecta a canales sin video activado.      | Mostrarte o tu pantalla.                 |
| **Usar panel de sonidos**             | Enviar sonidos desde panel del servidor.        | No permite sonidos externos.                 | Usar sonidos predefinidos.               |
| **Usar sonidos externos**             | Usar sonidos de otros servidores (Nitro).       | No crea sonidos nuevos.                      | Poner audios de fuera.                   |
| **Usar actividad de voz**             | Activar micro automáticamente sin pulsar tecla. | No silencia ruido si no tienes push-to-talk. | Hablar sin presionar un botón.           |
| **Prioridad de palabra**              | Reducir volumen de otros al hablar.             | No da volumen extra.                         | Que todos te escuchen claro.             |
| **Silenciar miembros**                | Mutear a otros en el canal.                     | No evita que entren.                         | Apagarles el micrófono.                  |
| **Ensordecer miembros**               | Quitarles la capacidad de escuchar y hablar.    | No expulsa.                                  | Silencio total para un usuario.          |
| **Mover miembros**                    | Pasar usuarios a otros canales.                 | No crea canales.                             | Arrastrar gente de un canal a otro.      |
| **Establecer estado de canal de voz** | Crear y modificar estados del canal.            | No gestiona roles.                           | Poner título o estado a un canal de voz. |

## 📜 Permisos de Aplicaciones y Eventos

| Permiso                           | Qué permite                                        | Qué no permite                                    | Explicación simple                     |
| --------------------------------- | -------------------------------------------------- | ------------------------------------------------- | -------------------------------------- |
| **Usar comandos de aplicaciones** | Usar slash commands y menús contextuales.          | No crea comandos nuevos.                          | Escribir `/` y usar funciones del bot. |
| **Usar actividades**              | Iniciar minijuegos o apps de Discord.              | No obliga a participar.                           | Jugar en voz con otros.                |
| **Usar aplicaciones externas**    | Permitir que apps publiquen mensajes en tu nombre. | No afecta bots con permisos propios.              | Que apps conectadas interactúen.       |
| **Crear eventos**                 | Hacer eventos programados.                         | No borra eventos ajenos.                          | Programar una reunión o juego.         |
| **Gestionar eventos**             | Editar o cancelar eventos.                         | No crea eventos si no tienes permiso de crearlos. | Modificar reuniones o actividades.     |

## 📜 Permisos Avanzados

| Permiso           | Qué permite                                | Qué no permite       | Explicación simple                 |
| ----------------- | ------------------------------------------ | -------------------- | ---------------------------------- |
| **Administrador** | Acceso total y bypass de permisos/canales. | Ninguna restricción. | Tener “todo el poder” sin límites. |
