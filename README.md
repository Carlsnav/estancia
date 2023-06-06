![Binaryhood](Logo/BinaryhoodLogo.png)

#ChatBot

## Instalación y configuración

[Instalar Python] https://www.dataquest.io/blog/installing-python-on-mac/

[Instalar pip] https://phoenixnap.com/kb/install-pip-mac

Si tiene instalado Python y pip, verifique su versión en la terminal o en las herramientas de línea de comandos

```
python3 --versión
```

```
pip --versión
```

## Instalación de matraz

En su terminal, ejecute el archivo requirements.txt usando este pip

```
pip install -r requisitos.txt
```


## Ejecutar la aplicación ChatBot en la terminal

```
cd en su directorio
```

```
python aplicación.py
```



## Lo que crearás

En este tutorial, lo guiaré a través del proceso de creación de un chatbot que pueda mantener conversaciones con los usuarios mediante el procesamiento de lenguaje natural.

Para comenzar, usaremos Microsoft DialoGPT, un modelo de lenguaje previamente entrenado que puede generar respuestas similares a las de los humanos a determinadas indicaciones. Integraremos DialoGPT con Flask, un marco web popular de Python, para crear una aplicación web que pueda comunicarse con los usuarios a través de una interfaz de chat.

Para la interfaz de nuestra aplicación, usaremos HTML, CSS y JavaScript para crear una interfaz de chat interactiva y visualmente atractiva. Además, usaremos jQuery para manejar las solicitudes HTTP que se realizan al servidor backend.

A lo largo del tutorial, proporcionaré instrucciones paso a paso sobre cómo configurar su entorno de desarrollo, instalar las dependencias necesarias y crear los archivos y el código necesarios para la aplicación. También explicaré cómo entrenar y ajustar el modelo DialoGPT para mejorar la precisión de sus respuestas.

Al final de este tutorial, tendrá un chatbot completamente funcional que puede entablar conversaciones con los usuarios y habrá adquirido una valiosa experiencia en el uso de Microsoft DialoGPT, Flask y tecnologías de desarrollo web como HTML, CSS y JavaScript.

# Enlace de chatbot
El Chatbot se construye usando el modelo mediano de Microsoft/DialoGPT.

```
https://huggingface.co/microsoft/DialoGPT-medium
```

# Usuario-Html

```
var userHtml = '<div class="d-flex allow-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ tiempo +
     '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg">< /div></div>';
```

#Bot-HTML

```
var botHtml = '<div class="d-flex allow-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt -512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></ div></div>';
```
