# 🚀 Despliegue de PokeDex en Azure Static Web Apps desde GitHub

Este documento detalla el procedimiento para desplegar la aplicación PokeDex desde un repositorio en GitHub utilizando **Azure Static Web Apps**.

---

## ✅ ¿Qué son Azure y GitHub?

### 🔹 Azure
Azure es una plataforma de nube de Microsoft que ofrece una variedad de servicios en la nube, como almacenamiento, bases de datos, redes y aplicaciones. Azure permite desplegar aplicaciones de forma escalable y gestionada, sin necesidad de preocuparse por la infraestructura.

#### ¿Cómo crear una cuenta en Azure?

1. Ve a [https://azure.microsoft.com](https://azure.microsoft.com)2. Haz clic en **"Iniciar sesión"** y luego en **"Comenzar gratis"** para crear una cuenta gratuita.3. Proporciona los datos requeridos, incluyendo un método de pago (no se te cobrará si no superas los 200 USD en créditos gratuitos durante los primeros 30 días).4. Sigue el proceso de verificación y confirma tu cuenta.




Una vez tengas tu cuenta de Azure, podrás acceder al **Azure Portal**, donde podrás crear, gestionar y desplegar tus aplicaciones.

---

### 🔹 GitHub
GitHub es una plataforma de desarrollo de software que permite almacenar, gestionar y compartir código fuente. Además, ofrece herramientas como GitHub Actions para automatizar flujos de trabajo como el despliegue continuo de aplicaciones.

#### ¿Cómo crear una cuenta en GitHub?

1. Visita [https://github.com](https://github.com)2. Haz clic en **"Sign up"** para crear una nueva cuenta.3. Completa el formulario de registro con tu nombre de usuario, correo electrónico y contraseña.4. Verifica tu correo electrónico y completa la configuración de tu cuenta.




Una vez registrado, podrás crear y gestionar tus repositorios para almacenar tu código fuente y colaborar con otros desarrolladores.

---

## ✅ Requisitos previos

- Cuenta en [Azure Portal](https://portal.azure.com)- Cuenta en [GitHub](https://github.com)- Repositorio con el proyecto (en este caso: [PoKeDeX1](https://github.com/Juansebblanco/PoKeDeX1))- Proyecto debe ser una app estática (HTML, CSS, JS o frameworks como React, Vue, Angular)




---

## 🧭 Paso a paso para el despliegue


### 1. Crear una Static Web App en Azure

1. Ingresa a [**PORTAL_AZURE**](https://portal.azure.com)
2.  Busca **Static Web Apps** y haz clic en **"Create"** 
3. Completa los siguientes campos:   - **Subscription:** tu suscripción activa   - **Resource Group:** crea uno nuevo (ejemplo: `PokeDexRG`)   - **Name:** nombre único (ejemplo: `pokedex-juanseb`)   - **Region:** selecciona la más cercana   - **Hosting plan type:** selecciona `Free`








### 2. Conectar con GitHub

1. En la sección **Deployment details**:   - Fuente: **GitHub**   - Autoriza tu cuenta de GitHub si es la primera vez   - Selecciona:     - **Organization:**`Juansebblanco`    
2.   **Repository:**`PoKeDeX1`    
3.  **Branch:**`main`



 
  


### 3. Revisión y despliege

1. Haz clic en **Review + Create**
2. Luego haz clic en **Create**
3. Espera unos minutos mientras se despliega la aplicación



---

## 🌐 Resultado del despliegue

Tu app será accesible desde la siguiente URL:

🔗 [***POKEDEX***](https://polite-bush-02974e510.6.azurestaticapps.net/)

---

## 📂 Código fuente del proyecto

El repositorio original se encuentra en:

🔗 [ **github.com/Juansebblanco/PoKeDeX1** ](https://github.com/Juansebblanco/PoKeDeX1)
