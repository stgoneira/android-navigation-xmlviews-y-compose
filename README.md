# Navegación Vistas XML y Compose 

## Notas

- El uso de ComposeView para usar Compose y evitar usar un XML 
- Lo anterior permite usar una Activity con Vista XML normal junto con Navigation y muchos fragmentos que pueden usar Compose o Vistas XML
- Importante ajustar las versiones para compatibilidad entre Kotlin y Compose

```kotlin
composeOptions {
    kotlinCompilerExtensionVersion '1.4.3'
    //kotlinCompilerExtensionVersion '1.3.2'
}

plugins {
    id 'com.android.application' version '8.0.2' apply false
    id 'com.android.library' version '8.0.2' apply false
    //id 'org.jetbrains.kotlin.android' version '1.8.20' apply false
    id 'org.jetbrains.kotlin.android' version '1.8.10' apply false
}
``` 

## Compatibilidad Versiones Kotlin y Compose 

https://developer.android.com/jetpack/androidx/releases/compose-kotlin?hl=es-419


## Cómo usar Vistas XML y Compose en un Proyecto 

- https://developer.android.com/jetpack/compose/migrate/interoperability-apis/compose-in-views?hl=es-419