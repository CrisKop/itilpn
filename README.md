# Guía para Configurar y Ejecutar el Proyecto

¡Bienvenido al proyecto! Sigue estos pasos para configurarlo y ejecutarlo en tu entorno local.

## Paso 1: Clonar el Proyecto

Para comenzar, clona el repositorio desde GitHub utilizando el siguiente enlace:

https://github.com/CrisKop/itilpn.git

Puedes clonar el repositorio ejecutando el siguiente comando en tu terminal:

```
git clone https://github.com/CrisKop/itilpn.git
```

## Paso 2: Instalar las Dependencias

Una vez que hayas clonado el proyecto, navega hasta la carpeta del proyecto en tu terminal y utiliza pnpm para instalar las dependencias:

```
cd itilpn
```
```
pnpm install
```

## Paso 3: Iniciar el Proyecto Localmente

Ahora que todas las dependencias están instaladas, puedes iniciar el proyecto localmente. Ejecuta el siguiente comando:

```
npm run dev
```

Esto iniciará la aplicación en tu entorno de desarrollo local. Abre tu navegador web y accede a `http://localhost:4321` para ver la aplicación en acción.

## Paso 4: Despliegue con Vercel (Opcional)

Si deseas desplegar la aplicación en línea, puedes utilizar Vercel. Para ello, sigue estos pasos:

1. Instala la herramienta Vercel globalmente (solo necesitas hacer esto una vez):

```
npm install -g vercel
```

2. Luego, despliega la aplicación con el siguiente comando:

```
vercel
```

Sigue las instrucciones de Vercel para configurar tu proyecto y desplegarlo en línea.

¡Listo! Ahora tienes el proyecto configurado y ejecutándose en tu entorno local, y puedes desplegarlo en línea si así lo deseas.

## Comandos de astro

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

<br>
<div style="text-align:center;">
  <img src="https://criskop.com/img/corona.png" alt="Corona" style="width: 200px;" />
   <p style="font-weight:bold; font-size: 60px;">CrisKop</p>
</div>


