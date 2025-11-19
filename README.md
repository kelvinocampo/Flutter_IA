## 🚀 Gemini Key Manager Chat

### **Tu Gestor de Claves de IA y Cliente de Chat Integrados en una Sola Aplicación Flutter**

<img src="./assets/README__preview.jpg" alt="Preview Chat IA" width="250"/>

---

### ⭐ Características Destacadas

Esta aplicación te permite centralizar el control de tus credenciales de Gemini con una experiencia de chat completa:

* **🔑 Gestión Segura de Claves:** Almacena, activa, edita y elimina hasta **10 API Keys de Gemini** de forma segura en tu dispositivo.
* **🗣️ Chat Impulsado por Gemini:** Utiliza la clave activa seleccionada para interactuar directamente con el modelo **Gemini 2.5 Flash** dentro de la aplicación.
* **🌐 Personalización Total:**
    * **Temas:** Alterna fácilmente entre el tema claro y oscuro.
    * **Idioma:** Soporte completo para **Inglés y Español**.
    * **Clave Activa:** Cambia la clave utilizada para las consultas en tiempo real desde la configuración.
* **🛡️ Almacenamiento Privado:** Todas tus claves se guardan localmente mediante almacenamiento seguro, garantizando tu privacidad.

---

### 📲 Cómo Empezar

#### 1. Obtener tu API Key de Gemini

Para usar la aplicación, primero necesitas una clave de acceso:

1.  Visita **Google AI Studio**: [https://aistudio.google.com/](https://aistudio.google.com/)
2.  Inicia sesión con tu cuenta de Google.
3.  Haz clic en **"Create API Key"** en la esquina superior derecha.
4.  Copia tu clave generada (el formato comienza con `AIzaSy...`).

#### 2. Usar la Aplicación

1.  **Instala la APK** (Disponible en la sección [Releases](#-releases)).
2.  Abre la aplicación y ve a la sección de **Configuración (Settings)**.
3.  Agrega tu clave usando el botón **"Crear nueva Key"**.
4.  Una vez agregada, asegúrate de que esté **activada**.
5.  Vuelve a la pantalla principal y comienza a chatear con Gemini.

---

### 💻 Instalación para Desarrollo (Flutter)

Si deseas contribuir o probar el código fuente:

1.  **Clona el Repositorio:**
    ```bash
    git clone [https://github.com/kelvinocampo/TestFlutter](https://github.com/kelvinocampo/TestFlutter)
    cd TestFlutter
    ```
2.  **Instala las Dependencias:**
    ```bash
    flutter pub get
    ```
3.  **Ejecuta la Aplicación:**
    ```bash
    flutter run
    ```

#### **Detalles Técnicos:**

| Componente | Tecnología/Modelo |
| :--- | :--- |
| **Modelo Base** | `gemini-2.5-flash` |
| **Gestión de Estado** | Provider |
| **Internacionalización** | `flutter_localizations` |
| **Almacenamiento (Keys)** | `sqflite` (Para claves seguras) |
| **Almacenamiento (Preferencias)** | `shared_preferences` |

---

### ⬇️ Releases

Encuentra la última versión estable (APK) y el historial de cambios aquí:

➡️ **[Últimas Versiones (Releases)](https://github.com/kelvinocampo/TestFlutter/releases)**

---

### 📄 Licencia

Este proyecto está licenciado bajo la [Licencia]. Ver el archivo [LICENSE] para más detalles.