# Demo Flask
Este proyecto utiliza Python 3.6.

## Dependencias
Para instalar las dependencias necesarias, siga estos pasos:

1. Abra una consola.
2. Vaya al directorio del proyecto (con el comando `cd`).
3. Escribe y ejecuta `pip3 install -r requirements.txt`.

## Inicializar base de datos
Para ejecutar la aplicación, debe proporcionar una cuenta de Microsoft para que la aplicación envíe o reciba correos electrónicos. Para agregar esta cuenta, siga estos pasos:

1. Abra el archivo `schema.sql`.
2. Localisa la linea `INSERT INTO credentials (name,user,password) VALUES ('EMAIL_APP','developmentcapstone', '$TR41NC0URS3R4$')`.
3. Remplaza `developmentcapstone` con tu dirrecion de Email.
4. remplaza `$TR41NC0URS3R4$` con la contraseña de tu Email.
5. Run `flask init-db` on the project directory.

## Run application
For run the app you need to use `flask run` on the project directory.
