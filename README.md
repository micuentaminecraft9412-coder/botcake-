# 🤖 Cake Bot

Bot para servidores anárquicos de Minecraft. Entra solo, se defiende, se cura,
acepta teletransportes y responde a comandos por susurro. Pensado para
jugarse sin estar pendiente todo el tiempo.

## ✨ Qué hace

- 🔑 Inicia sesión solo (login / registro, según lo que pida el servidor)
- 🧭 Entra al modo de juego aunque el servidor tenga una sala de espera
- 🍗 Come y se cura solo, sin quedarse con hambre
- 🛡️ Se defiende de mobs hostiles automáticamente
- 📨 Responde a comandos por susurro (`/msg`)
- ➡️ Acepta teletransportes (`/tpa`) de quien tú autorices
- ⚙️ Todo se configura desde un solo archivo, sin tocar código

## 📦 Dos versiones disponibles

| Versión | Para quién es |
|---|---|
| **Versión completa** | Ya trae todo instalado. Descomprime y arranca. |
| **Versión sin dependencias** | Más liviana. Hay que correr un comando para instalar lo que falta (se explica en la guía). |

Descarga cualquiera de los dos `.zip` de este repositorio.

## 🚀 Cómo empezar

1. Descarga el `.zip` que prefieras.
2. Descomprímelo en una carpeta.
3. Sigue la guía de instrucciones incluida adentro (`como-usar-config.txt` o
   `como-usar-config-version-ligera.txt`, según la versión que bajaste).
4. Copia `config.example.json`, renómbralo a `config.json` y pon tus datos.
5. Arranca el bot con:

   ```
   node NOMBRE_DEL_ARCHIVO.js
   ```

Todos los pasos detallados, con capturas de qué escribir en la consola, están
en el archivo de instrucciones dentro del `.zip`.

## 🛠️ Configuración

Todo se ajusta en `config.json`: el servidor, el nombre del bot, quién es el
dueño, quién puede pedirle teletransporte, y más. No hace falta tocar el
código para nada de esto.

## 📜 Licencia

Este proyecto es de código cerrado. Revisa el archivo [LICENSE](./LICENSE)
antes de usarlo o compartirlo.

Usa las librerías `mineflayer`, `mineflayer-pathfinder` y `minecraft-data`,
cada una bajo su propia licencia MIT.
