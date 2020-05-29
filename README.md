# unity-multidex

1. Ir a `Edit -> Preferences -> Player -> Android -> Publishing Settings`.

2. Habilitar el archivo Gradle personalizado haciendo click en `Custom Gradle Template`.

3. Marcar la opción `Custom Main Gradle Template` y se generará el archivo en la carpeta `Assets`.

  ![](a.png)

4. Editar el archivo `Assets/Plugins/Android/mainTemplate.gradle` y habilitar la opción multiDex:

  ![](b.png)

Referencia: [Habilitar MultiDex en un proyecto Unity](https://appmediation.com/unity-enable-multidex/).
