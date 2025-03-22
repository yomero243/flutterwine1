# FlutterWine App

Una aplicación Flutter que combina autenticación con Supabase y funcionalidad de WebView.

## Características

- Autenticación de usuarios utilizando Supabase
- Visualización de contenido web a través de WebView
- Diseño moderno con Material 3

## Configuración

1. Crea un archivo `.env` en la raíz del proyecto con el siguiente contenido:
   ```
   SUPABASE_URL=tu_url_de_supabase
   SUPABASE_ANON_KEY=tu_clave_anonima_de_supabase
   ```

2. Reemplaza los valores con tus credenciales reales de Supabase.

3. Ejecuta `flutter pub get` para instalar las dependencias.

4. Ejecuta la aplicación con `flutter run`.

## Dependencias principales

- flutter_dotenv: Para manejar variables de entorno
- supabase_flutter: Para autenticación y backend como servicio
- webview_flutter: Para mostrar contenido web dentro de la aplicación

## Estructura del proyecto

- `lib/main.dart`: Punto de entrada de la aplicación y pantalla de inicio de sesión
- `lib/webview_page.dart`: Página que muestra contenido web utilizando WebView

## Permisos

La aplicación requiere permisos de Internet para funcionar correctamente tanto para Supabase como para WebView.
