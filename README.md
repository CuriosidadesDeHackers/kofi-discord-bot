<a href='https://ko-fi.com/O4O3W3IIA' target='_blank'>
  <img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi5.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' />
</a>

# kofi-discord-bot

Aplicación Serverless Express ejecutándose en funciones de Netlify para enviar notificaciones de Ko-fi a Discord.

## 📦 Ko-fi

### 🤔 ¿Por qué?
Ko-fi actualmente tiene una integración con Discord que solo realiza la asignación de roles, pero no envía notificaciones de mensajes al recibir una donación. Encontré un script en Node.js para lograr este objetivo, pero desafortunadamente necesitaba un entorno de servidor en ejecución constante, así como tu propio dominio para evitar exponer la dirección IP del servidor. Por lo tanto, lo modifiqué para que se ejecute en Netlify Functions, y también obtienes un subdominio gratuito de Netlify.

También puedes desplegar este sencillo script en un sitio web de Netlify ya existente si tienes uno. Solo recuerda incluir las dependencias adicionales en tu `package.json` principal y actualizar tus variables de entorno.

### 🛠 ¿Cómo?

1. **Haz clic en este botón:**

   [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/your-repo)

2. **Rellena tus variables de entorno:**

![1](https://github.com/user-attachments/assets/8168014f-951c-449c-b90e-942a659f92d5)

3. **Guarda y despliega:**

   Accede a tu función en: `https://<tu_dominio>.netlify.app/.netlify/functions/kofi`

![2](https://github.com/user-attachments/assets/6544d9ec-8086-4744-a9a4-b9429c7170de)

4. **Edita tu URL de Webhook en Ko-fi:**

5. **Prueba tu webhook:**

![4](https://github.com/user-attachments/assets/215b0700-d956-4de2-8be1-74258c1655e6)

### 📍 ¿Dónde?

- **URL de Webhook de Discord** (En la configuración del canal):

- **Token de Ko-fi** (En configuración avanzada):

![3](https://github.com/user-attachments/assets/00a1fec2-cda0-4d9f-ab95-40a28a353a9c)

### 🆘 Ayuda

Siéntete libre de contactarme en Discord o crear un issue en este repositorio.


