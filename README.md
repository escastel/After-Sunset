🌅 After Sunset
=============================
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9+-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-API%2026+-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-UI-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Firebase](https://img.shields.io/badge/Firebase-Backend-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)

**After Sunset** es una propuesta disruptiva en el ecosistema de aplicaciones de ocio nocturno. No es solo una ticketera; es una ventana inmersiva a la vida de la ciudad cuando cae el sol. Diseñada con un enfoque Mobile-First y una estética Cyber-Night, After Sunset redefine la forma en que los usuarios descubren, viven y comparten la noche malagueña.



https://github.com/user-attachments/assets/62bea5b5-e4fe-4aa9-b5d6-b402f2aaf40a



---

## ✨ Características Principales

*   🌌 **Diseño Inmersivo "Cyber-Night"**: Interfaz de usuario moderna y oscura construida con **Jetpack Compose**, utilizando degradados dinámicos y animaciones fluidas.
*   📍 **Geolocalización en Tiempo Real**: Integración con **Google Maps SDK** para visualizar locales abiertos, filtrar por zonas de Málaga y obtener rutas directas.
*   🎟️ **Ticketing Inteligente**: Sistema de compra de entradas integrado con generación de **códigos QR** únicos para el control de acceso.
*   🤖 **Avatares Dinámicos**: Integración con la **API de DiceBear** para generar fotos de perfil aleatorias y estilizadas (estilo *bottts*) para cada usuario.
*   👥 **Ecosistema Social**: Gestión de amistades, búsqueda de usuarios por `@username` y sistema de reseñas con valoración por estrellas.
*   🏆 **Fidelización**: Sistema de rangos dinámicos (Standard, VIP, Gold, Legendary) basado en la participación del usuario.

---

## 🛠️ Stack Tecnológico

*   **Lenguaje:** [Kotlin](https://kotlinlang.org/)
*   **UI Framework:** [Jetpack Compose](https://developer.android.com/jetpack/compose)
*   **Arquitectura:** MVVM (Model-View-ViewModel) + Repository Pattern.
  ```
com.example.aftersunset/
├── data/           <-- Implementaciones de Firebase y Repositorios.
├── domain/         <-- Modelos de datos (Event, User) e Interfaces.
├── navigation/     <-- Rutas @Serializable y NavHost principal.
├── ui/
    ├── theme/      <-- Colores, Tipografías y Formas.
    ├── components/ <-- Componentes reutilizables (Botones, Cards).
    └── screens/    <-- Pantallas (Login, Home, Map, etc.).
```
*   **Navegación:** Type-Safe Navigation (Type-safe routes con Kotlin Serialization).
*   **Inyección de Dependencias:** Gestión manual orientada a la simplicidad y escalabilidad.
*   **Backend:** 
    *   **Firebase Auth:** Gestión de identidad de usuarios.
    *   **Cloud Firestore:** Base de datos NoSQL escalable en tiempo real.
*   **Librerías de Terceros:**
    *   **Coil 3:** Carga de imágenes asíncrona y eficiente.
    *   **Lottie:** Animaciones vectoriales de alta calidad.
    *   **DiceBear API:** Generación procedimental de avatares.

---

📦 Instalación
--------------
Si deseas probar el proyecto localmente, consulta nuestro [Manual de Instalación](./MANUAL_INSTALACION.md). 

1.  Clona el repositorio.

2.  Asegúrate de tener **Android Studio**.

3.  Sincroniza el proyecto con Gradle.

4.  Pide el archivo `google-services.json` para conectar con Firebase.

5. Pide el valor de `MAPS_API_KEY` que necesitas colocar en **local.properties**

---

## 🎓 Proyecto Final (TFG)

Este proyecto ha sido desarrollado como el **Proyecto Intermodular de Fin de Ciclo (TFG)** para el Grado Superior de **Desarrollo de Aplicaciones Multiplataforma (DAM)**. 

El objetivo principal ha sido demostrar la capacidad de crear una solución móvil completa y escalable, poniendo especial énfasis en una **experiencia de usuario (UX)** y en la implementación de las últimas tecnologías y patrones de diseño recomendados por Google para el desarrollo nativo moderno en Android.

