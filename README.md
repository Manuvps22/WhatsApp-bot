# MANUVPS Bot

Descripción breve del bot, cómo usarlo y qué hace…

## Instalación

(Explicación como en tu README anterior)

## Uso

- !menu
- !yt <url>
- !fb <url>
- !apk <url>

## Terminal

- `/send <número> <mensaje>`
- `/exit`
- #!/bin/bash

echo "🛠️ Instalación del WhatsApp Bot MANUVPS"

# Actualizar paquetes
pkg update -y && pkg upgrade -y

# Instalar dependencias
pkg install -y git nodejs

# Clonar el repositorio (cambia la URL si es tuyo)
git clone https://github.com/TU_USUARIO/MANUVPS.git
cd MANUVPS || exit

# Instalar módulos de Node.js
npm install

echo "✅ Instalación completa."
echo "🚀 Ejecutando el bot..."

# Iniciar el bot
node index.js
