# 💻 Universidad Politécnica Territorial de Puerto Cabello (UPTPC)

<p align="center">
  <a href="https://www.uptpc.edu.ve/">
    <img src="https://i.ibb.co/ZzBd0nQ1/LOGO.png" alt="Logo de la UPTPC" width="200"/>
  </a>
</p>


## 🚀 Repositorio de Configuración para Proyectos de Estudiantes

Este repositorio nace con la finalidad de centralizar y facilitar la configuración de las subidas de archivos en los sistemas desarrollados por los estudiantes de la Universidad Politécnica Territorial de Puerto Cabello (UPTPC).

---

### Guía para crear tu repositorio personal de proyecto

A continuación, te explicamos el proceso para crear tu repositorio de Proyecto Sociotecnológico de manera automática dentro de la organización UPTPC. Este proceso es rápido y te garantiza que tu repositorio esté listo para ser usado con las configuraciones adecuadas.

**Paso 1: Ir a la herramienta de creación**
Ve a la siguiente página web para comenzar:
https://uptpc.github.io/proyecto-automatizacion/

**Paso 2: Completar el formulario**
En la página, encontrarás dos campos:

* **Nombre del Repositorio:** Escribe un nombre corto y descriptivo para tu repositorio (máximo 80 caracteres).

* **Descripción Completa del Proyecto:** Ingresa el título Completo de tu Proyecto Sociotecnológico.

**Paso 3: Iniciar la solicitud**
Una vez que hayas completado los campos, haz clic en el botón con el ícono de GitHub: **"Ir a GITHUB a Crear el Repositorio"**. Esto te llevará a una página de GitHub.

**Paso 4: Confirmar la creación en GitHub**
Una vez redirigido a la página de creación de *issue* en nuestro repositorio de automatización. El título y el cuerpo del *issue* ya estarán pre-rellenados. Para confirmar tu solicitud, simplemente haz clic en el botón verde **"Create"**.

**Paso 5: Esperar la confirmación**
Una vez que hayas confirmado, nuestro sistema de automatización (GitHub Actions) se activará. En unos segundos o un par de minutos, se creará tu repositorio y recibirás un comentario en el *issue* con el enlace directo a tu nuevo espacio de trabajo.

### **Paso 6: Aceptar la Invitación de Colaborador**

¡Atención! 🚨 Tu repositorio ha sido creado, pero para poder subir tus archivos necesitas aceptar la invitación a ser colaborador. Revisa tu correo electrónico 📧 o ve directamente a la sección de invitaciones de tu repositorio.

👉 **Enlace directo a las invitaciones:** En el *issue* veras un mensaje que te invita a aceptar la invitacion a colaborar y se muestra un link como este: `https://github.com/UPTPC/TU-REPOSITORIO/invitations`

Una vez que aceptes, tendrás permisos de escritura (`write`) y podrás clonar los archivos desde tu computadora y subir los archivos de tu proyecto sin problemas.

---

### 🔑 Configuración de Autenticación para subir archivos

Si después de aceptar la invitación tienes problemas para subir tu proyecto, es posible que tu cliente de Github (o Visual Studio Code) esté usando credenciales antiguas. Aquí te explicamos cómo solucionarlo:

#### **🚀 Para Usuarios de Visual Studio Code**

1. **Clona el Repositorio:** Usa la URL HTTPS para clonar el repositorio en tu máquina. Reemplaza `TU-REPOSITORIO` con el nombre de tu repositorio, recuerda que nuestro sistema te va a suminsitrar el link correcto usando la convension para tal fin.

   ```
   git clone [https://github.com/UPTPC/TU-REPOSITORIO.git](https://github.com/UPTPC/TU-REPOSITORIO.git)
   ```

2. **Haz tu primer `commit`:** Añade tus archivos y haz un `commit` localmente.

3. **Intenta un `push`:** Cuando intentes subir tus cambios (hacer `push`), Visual Studio Code te pedirá autenticarte.

4. **Usa tu Token de Acceso Personal:** Cuando te pida la contraseña, no uses la contraseña de tu cuenta de GitHub. En su lugar, utiliza el **Token de Acceso Personal (PAT)** que creaste. Si no te funciona, es posible que debas cerrar y volver a abrir Visual Studio Code para que reconozca las nuevas credenciales.

#### **💻 Para Usuarios de Windows (Git Credential Manager)**

1. **Abre el Administrador de Credenciales:** Presiona la tecla de Windows, escribe "Administrador de credenciales" y ábrelo.

2. **Busca las credenciales de Git:** En la sección "Credenciales de Windows", busca las entradas que comienzan con `git:https://github.com`.

3. **Elimina las credenciales antiguas:** Haz clic en la entrada y selecciona "Eliminar". Esto borrará las credenciales guardadas.

4. **Intenta un `push` nuevamente:** Cuando vuelvas a intentar subir archivos, Git te pedirá tu nombre de usuario y **el Token de Acceso Personal (PAT)** como contraseña.

#### **🐧 Para Usuarios de Linux (Terminal)**

1. **Usa `git config`:** Desde la terminal, puedes forzar a Git a olvidar las credenciales guardadas con el siguiente comando:

   ```
   git config --global --unset credential.helper
   ```

2. **Intenta un `push` nuevamente:** Cuando subas tus cambios, la terminal te pedirá tu nombre de usuario y **el Token de Acceso Personal (PAT)** como contraseña.

---

### **Paso 7: Empezar a trabajar**

¡Felicidades! 🎉 Tu repositorio ya está listo. Puedes ir al enlace proporcionado en el comentario, clonar el repositorio y comenzar a subir los archivos de tu proyecto.

---

Actualmente en la Universidad Politecnica Territorial de Puerto Cabello ofrecemos una amplia gama de estudios de pregrado:

**Programas Tradicionales (PT) - Título de T.S.U:**
* Mecánica Térmica
* Mecánica Automotriz

**Programas Nacionales de Formación (PNF) - Título de T.S.U. e Ingeniero(a) o Licenciado(a):**
* Materiales Industriales
* Mantenimiento
* Mecánica
* Turismo
* Informática
* Distribución y Logística

🌐 [Visita nuestra web oficial](https://www.uptpc.edu.ve/)

---

### 🌐 Repositorio Institucional en Telegram
Únete a nuestra comunidad y mantente al día con las novedades del SEREINF y los proyectos de la universidad.

[**Canal de Telegram Jornaltec**](https://t.me/jornaltec)
