# unity-multidex

1. Habilitar el archivo Gradle personalizado en `Edit -> Preferences -> Player -> Android -> Publishing Settings` haciendo click en `Custom Gradle Template`.

2. Marcar la opción `Custom Main Gradle Template` y se generará el archivo en la carpeta `Assets`.

  ![](a.png)

3. Editar el archivo `Assets/Plugins/Android/mainTemplate.gradle` y habilitar la opción multiDex:

  ![](b.png)

Referencia: [Habilitar MultiDex en un proyecto Unity](https://appmediation.com/unity-enable-multidex/).
