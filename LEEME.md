# AI Forward · KPMG × Spiralia

Briefing de servicios para KPMG España: del aula al trabajo real, con el método SPIRAL. Es una web de 30 pantallas, montada sobre el mismo motor que la propuesta AImagine de ING y con la identidad digital actual de KPMG.

## Cómo abrirla

- **Servidor local.** Hay que servir la carpeta `ai-forward/` con uno: los vídeos y las fuentes no cargan si se abre como archivo. La configuración `ai-forward` de `.claude/launch.json` lo hace en `http://localhost:8793`.
- **Navegación:**
  - menú superior por capítulos;
  - flechas del teclado o botones ↑ ↓;
  - `Inicio` y `Fin` para ir al principio o al final;
  - `M` pausa o activa el movimiento;
  - `A` repite la animación de la pantalla.
- **Pantallas bajas.** En portátiles, el contenido se reduce solo para que quepa en el alto de la ventana.

## Publicarla

Sube la carpeta `ai-forward/` tal cual a Vercel o a cualquier hosting estático, igual que la de ING. Lleva `noindex`, así que los buscadores no la indexan.

## PDF

Imprime desde Chrome con «Guardar como PDF», márgenes «Ninguno» y gráficos de fondo activados. Sale una página de 1600×1000 por pantalla. Hay una exportación hecha en `../AI_Forward_KPMG_Spiralia.pdf`.

## Estructura

| Capítulo | Pantallas |
|---|---|
| Spiralia | 01 Portada (vídeo) · 02 Quiénes somos (equipo, logos, 50.000+) · 03 Lo que ya hacemos (ING y CCEP) · 04 Cinco principios |
| Contexto | 05 80 % frente a 6 % · 06 Primera gran pregunta · 07 La inteligencia se compra, la ventaja se despliega · 08 La eficiencia tiene techo; el crecimiento, no |
| Respuesta | 09 Segunda pregunta · 10 El trabajo real no cabe en un procedimiento · 11 Dos formas de ayudar, un solo recorrido · 12 Tercera pregunta · 13 El FDE |
| SPIRAL | 14 Cuarta pregunta · 15 Nube que se ordena · 16 La espiral · 17 Cada vuelta · 18–23 S, P, I, R, A, L · 24 Seis compromisos *by design* |
| Práctica | 25 Caso animado: la propuesta comercial (ilustrativo) |
| Autonomía | 26 Quinta pregunta · 27 Modelo de gobierno (roles, procesos, sistemas) · 28 De construirlo juntos a construirlo vosotros |
| Empezar | 29 ¿Por dónde empezamos? · 30 Cierre (vídeo) |

## Fuentes y reglas de contenido

- **McKinsey, *The state of AI in 2026*** (agosto de 2026): pp. 3, 4, 14, 17 y 18. La cita de la p. 14 es una paráfrasis.
- **ING:** programa de adopción de IA de Spiralia en ING España; medición interna del grupo, con uso externo autorizado.
- **CCEP:** programa CCEP Iberia × Spiralia, julio de 2026.
- **Credenciales y equipo:** facilitados por Spiralia. La trayectoria de Pedro Valero sale de su perfil de LinkedIn (consultado el 6-oct-2026); su foto está pendiente y de momento aparecen sus iniciales.
- **Lo que no lleva:** plazos, precios, datos de KPMG, menciones a Uber ni el logotipo de KPMG entre los clientes.
- **Etiquetas:** el caso (25), la matriz de pruebas (22) y los gráficos de las pantallas 08 y 28 van marcados como ilustrativos.

## Activos

- **`assets/cover-video.mp4` y `cover-poster.jpg`:** portada AI FORWARD (22,2 s). Su proyecto está en `../motion/portada_kpmg/`, con su propio LEEME.
- **`assets/closing-video.mp4`:** fondo del cierre (el semáforo).
- **Logos de KPMG:** `kpmg.svg` y `kpmg-white.svg`, oficiales de kpmg.com.
- **Logo de Spiralia:** `spiralia.png`.
- **Clientes:** `logo-*.svg/png` e `ing.svg`.
- **Fotos del equipo:** `*.jpg`.
- **Tipografía:** Open Sans variable, licencia OFL, de Google Fonts.
