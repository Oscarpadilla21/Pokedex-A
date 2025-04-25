# Creación de Cuenta en Vercel y Despliegue de la aplicacion 🚀

Este tutorial te guiará a través del proceso de **creación de una cuenta en Vercel**, la plataforma que usaremos para desplegar la aplicación  `pokedex-angular(en este caso Pokedex-A)`. 

## Requisitos Previos 📝

Antes de comenzar, asegúrate de tener lo siguiente:

- **Una dirección de correo electrónico válida** 📧.
- **Una cuenta en GitHub**  🛠️.
- **Proyecto subido en  un repositorio de GitHub**
- **Un navegador web** actualizado (Chrome, Firefox, Safari, etc.) 🌐.

## Paso 1: Visitar el Sitio Web de Vercel 🌍

1. Abre tu navegador web y visita [vercel.com](https://vercel.com).

## Paso 2: Registro 🆕

1. Haz clic en el botón  en la esquina superior derecha(Tiene un icono de 3 rayas).
2. Después de hacer clic nos desplegara varias opciones, le daremos clic al que dice Sign Up 
3. Seleccionaremos el plan de Hobby para proyectos personales en nuestro caso.
4. Después ingresaremos nuestro nombre en el input que apareció. 
5. Regístrate utilizando una de las siguientes opciones:
   - **GitHub** 🐙(Esta es la que usaremos en nuestro caso)
   - **GitLab** 🦊
   - **Bitbucket** 🦋
   - **Correo electrónico** ✉️

## Paso 3: Autorización (para GitHub, GitLab o Bitbucket) 🔑

1. Si eliges GitHub, GitLab o Bitbucket, serás redirigido a la página de autorización correspondiente.
2. Inicia sesión y **autoriza a Vercel** para acceder a tus repositorios. Esto permitirá que Vercel pueda realizar el despliegue de tus proyectos directamente desde tu cuenta de control de versiones.

## Paso 4: Configuración Inicial ⚙️

1. Crea un equipo nuevo para desplegar el proyecto `Pokedex-angular` 
2. Sigue el breve **tutorial de configuración** de Vercel o sáltalo si prefieres. Este tutorial te ayudará a familiarizarte con las funcionalidades de la plataforma.

## Paso 5: Confirmación del Correo Electrónico ✔️

1. Revisa tu bandeja de entrada y busca un correo de verificación de Vercel.
2. Haz clic en el **enlace de verificación** para confirmar tu cuenta. Esto es importante para activar todas las funcionalidades de tu cuenta y no tener problema alguno.

---
## Paso 6:Despliegue del proyecto

 1. En el panel principal de vercel le daremos a Add New.
 2. Se nos desplegaran varias opciones, le daremos a Project.
 3. En pantalla nos saldrán los repositorios que tenemos para desplegar, seleccionaras el proyecto Pokedex-A(Si le cambiaste el nombre a el proyecto, usa el que tenga el nombre que colocaste) y le daras import.
 4. En pantalla te saldrá **NEW Project** donde podrás ponerle un nombre al proyecto dentro de vercel, Framework Preset, Build and Outpu Settings y Enviorement Variables.
 5. En **Build and Output Settings** habilitaremos la opcion de Build Command y colocaremos **npm run build**
 6. Tambien habilitaremos la opcion de Install Command y colocaremos **npm install**
 7. Presionaremos el boton que dice **Deploy** y esperamos a que nuestro sitio sea desplegado públicamente

¡Listo! 🎉 Ahora deberia estar desplegado el sitio y podria entrar desde la URL que se la ha dado en vercel🌟
