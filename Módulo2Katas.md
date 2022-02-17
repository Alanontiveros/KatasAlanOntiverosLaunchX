# Ejercicio - Crear un paquete

En este ejercicio se ejecuto desde terminal un entorno virtual como una forma para no afectar a los paquetes instalados globalmente.

## Crear un entorno virtual

Crear un entorno virtual mediante `venv`

* Ejecutar en terminal:  `python -m venv env`

  ```
     python -m venv env 
  ```

  Se ha creado un directorio (folder) `env` desde la terminal.

  ![img](https://file+.vscode-resource.vscode-webview.net/c%3A/Users/Alano/Desktop/Launchex/image/M%C3%B3dulo2Katas/1645061417088.png)
* Se ejecuto el comando para activar el entorno virtual: `env\Scripts\activate `

  ```
  env\Scripts\activate
  ```

  ![](image/Módulo2Katas/1645061633591.png)

Ahora en terminal se puede apreciar  `(env)`. Lo cual da por hecho que se ha activado el entorno virtual y se ha aislado del resto de la máquina.

![](image/Modulo2Katas/1644545144123.png)

## Instalar una biblioteca

* Se ejecuta el comando `pip freeze` para ver las bibliotecas instaladas en tu entorno que en este caso no existe ninguna instalada:

  ```
  pip freeze
  ```

  ![img](image/Módulo2Katas/1645062322066.png)
* Se ejecuta el comando `pip install` para instalar una biblioteca:

  ```
  pip install python-dateutil
  ```

  ![](image/Módulo2Katas/1645062383615.png)
* Volvemos a ejecutar `pip freeze` para ver cómo ha cambiado tu lista de bibliotecas:

  ```
  pip freeze
  ```
* Se muestra la siguiente lista:


  ```
  python-dateutil==2.8.2
  six==1.16.0
  ```

![](image/Modulo2Katas/1644545233509.png)![](image/Módulo2Katas/1645062440439.png)

### Desactivar un entorno virtual

Ejecuta el comando `deactivate`:

```
deactivate
```

Se elimina el mensaje de la terminal `(env)` mostrado anteriormente.

![](image/Modulo2Katas/1644545296221.png)![](image/Módulo2Katas/1645062469601.png)
