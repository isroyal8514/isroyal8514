# ¡Hola! Soy Israel Reyes 🇵🇦👋

Soy un estudiante de duodécimo grado de bachillerato en tecnología en el Colegio Rodolfo Chiari. Me apasiona profundamente entender cómo funcionan las computadoras, optimizar mis propios sistemas operativos y construir soluciones tecnológicas reales a los problemas del día a día. 

Actualmente utilizo **Linux (Debian)** como mi sistema principal, el cual instalé desde cero en un disco duro externo para armar mi propio entorno de trabajo personalizado y enfocarme en la programación y la automatización. Mi meta a corto plazo es ingresar a la universidad, para lo cual me estoy preparando firmemente para la prueba de admisión de este 1 de agosto.

---

## 🛠️ Mis Tecnologías y Herramientas
- **Sistemas Operativos & Entornos:** Linux (Debian, Kali, entorno Hyprland/Wayland).
- **Desarrollo Web & Backend:** HTML5, CSS3, JavaScript, Firebase (Bases de datos de Google).
- **Programación & Automatización:** Python, Git y GitHub.
- **Hardware & Robótica:** Arduino, microcontroladores, servomotores y sensores.

---

## 📁 Proyectos Destacados

### 1. 🌐 Panamá Nexus (Plataforma Web de Estudio)
Nació hace un mes por una necesidad personal: quería estudiar para mi examen de admisión universitaria, pero necesitaba medir mi progreso real, llevar el control de mis puntajes y evitar responder al azar. 
- **Desarrollo:** Utilicé herramientas de IA (Claude) para guiarme en el diseño de la interfaz en HTML/CSS, y estructuré la lógica en JavaScript mediante Visual Studio Code.
- **Innovación con Firebase:** Inicialmente la web guardaba los datos en la caché del navegador, pero si esta se borraba, perdía mi progreso. Para solucionarlo, integré **Firebase** para gestionar usuarios (con inicio de sesión para miembros e invitados) y almacenar el progreso en la nube de forma segura.
- **Estado actual:** El sitio cuenta con un panel de administrador para gestionar comentarios de usuarios y revisar la base de datos. Aunque sigue en desarrollo y mejora continua, cumple perfectamente su objetivo principal: guiar mi aprendizaje.

### 2. 🤖 Proyecto de Robótica y Microcontroladores (CSI)
Formo parte del **Cuerpo de Solidaridad Informático (CSI)**, donde profundizamos en tecnología aplicada. En nuestro taller práctico desarrollamos un sistema de control de hardware.
- **¿Qué hace?:** Programamos un microcontrolador (que, como sé, integran todo en un solo chip y están en todos lados, desde microondas hasta teléfonos) para manipular servomotores mediante un joystick físico.
- **Desafío técnico:** Implementamos la lógica matemática inversa en el código Arduino para que el motor girara de forma opuesta ($180^\circ$ menos el valor ingresado) según los movimientos del joystick. También trabajamos con resistencias pull-up para asegurar el correcto funcionamiento de los botones de control y evitar que los componentes se quemaran. *(Toda la documentación técnica y diagramas los tengo organizados en el PDF del proyecto).*

### 3. 👁️ Ojo de Neón (v6.6 PRO)
Es un script de automatización y visión artificial desarrollado en **Python** con la guía de Gemini, diseñado especialmente para optimizar tareas en entornos Linux mediante atajos de teclado.
- **Lectura inteligente de QR:** Al presionar un atajo, el script abre la terminal, enciende la cámara y lee códigos QR. Si detecta un código de Wi-Fi, extrae la contraseña, la almacena y se conecta automáticamente si la red está al alcance. También gestiona textos directo al portapapeles.
- **Seguridad y Control de Comandos:** Una de sus funciones más avanzadas es la ejecución de comandos de sistema desde un QR. Para evitar riesgos (como que un código malicioso intente formatear el equipo), implementé un sistema de seguridad que analiza el código, me describe en la terminal qué es lo que va a hacer y me pide confirmación explícita antes de ejecutarlo. La terminal se mantiene abierta esperando mis órdenes (`q` o `enter`) para cerrar el ciclo.

---

> *"No lo sé todo, pero tengo la iniciativa y la capacidad de buscar la información, seguir guías, entender el código y solucionar los problemas tecnológicos que me propongo."*
