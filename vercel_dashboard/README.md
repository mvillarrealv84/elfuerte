# Dashboard Global de Auditoría de Pipas (Vercel + Supabase)

Este proyecto contiene el Dashboard Web en la Nube para supervisar las tomas de agua desde cualquier parte del mundo.

---

## 🚀 Despliegue en Vercel

Tienes dos formas sencillas de desplegarlo:

### Método 1: Desde la Terminal (Recomendado)
Abre PowerShell o Símbolo del Sistema en esta carpeta (`vercel_dashboard`) y ejecuta:

```powershell
npx.cmd vercel
```
* Sigue las instrucciones en pantalla (inicia sesión con tu cuenta de Vercel/GitHub si te lo pide).
* Selecciona las opciones por defecto (presionando `Enter`).
* ¡En menos de 30 segundos te dará tu enlace en vivo! (Ejemplo: `https://auditoria-pipas.vercel.app`).

---

### Método 2: Desde GitHub
1. Sube los archivos de esta carpeta a un repositorio en tu GitHub.
2. Entra a [vercel.com](https://vercel.com) -> **Add New...** -> **Project**.
3. Selecciona tu repositorio y haz clic en **Deploy**.

---

## ⚡ Características Incluidas
* **Tiempo Real:** Se actualiza automáticamente cuando la Raspberry Pi detecta una pipa sin necesidad de refrescar la pantalla.
* **Fotos en Alta Resolución:** Las fotos se cargan a máxima velocidad desde el CDN público de Supabase Storage.
* **Auditoría de Vales:** Permite cotejar los vales entregados contra las pipas registradas y marca faltantes de inmediato.
* **Exportación Excel (CSV):** Descarga reportes completos con enlaces directos a las evidencias.
