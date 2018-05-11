
# Chatbot para: Facebook Messenger
Esta es una plantilla simple de Python que usa Flask para construir un "webhook" valida para la API "Messenger-Bot" de Facebook.

## Me "Falló la verificación de devolución de llamada" ! D:

Lea bien compa... y declara aun mejor


![Error de Facebook?](https://cloud.githubusercontent.com/assets/18402893/21538944/f96fcd1e-cdc7-11e6-83ee-a866190d9080.png)

El error n. ° 1 que se informa en los problemas es que Facebook devuelve un mensaje de error (como el anterior) al intentar agregar el extremo heroku a su aplicación de chat de Facebook.

Nuestra aplicación de matraz devuelve intencionalmente un error prohibido 403 si el token que Facebook envía no coincide con el token que configura utilizando las variables de configuración de heroku.

Si obtiene este error, probablemente signifique que no configuró correctamente sus valores de configuración de heroku. Ejecute `heroku config` desde la línea de comando dentro de su aplicación y verifique que haya una clave llamada` VERIFY_TOKEN` que se haya configurado, y que esté configurada con el mismo valor que la que escribió en la ventana de Facebook. #

# Facebook Messenger Bot
This is a simple python template that uses Flask to build a webhook for Facebook's Messenger Bot API.

## "Callback verification failed"

![Facebook Error](https://cloud.githubusercontent.com/assets/18402893/21538944/f96fcd1e-cdc7-11e6-83ee-a866190d9080.png)

The #1 error that gets reported in issues is that facebook returns an error message (like above) when trying to add the heroku endpoint to your facebook chat application.

Our flask application intentionally returns a 403 Forbidden error if the token that facebook sends doesn't match the token you set using the heroku configuration variables.

If you're getting this error, it likely means that you didn't set your heroku config values properly. Run `heroku config` from the command line within your application and verify that there's a key called `VERIFY_TOKEN` that has been set, and that it's set to the same value as what you've typed into the window on facebook.#
