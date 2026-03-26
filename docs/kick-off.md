# 🚀 Documento de Kick-off: El Fulbo y Yo

## 1. Definición del MVP (Fase 1)
El lanzamiento inicial se centrará en la identidad del jugador:
- [ ] **Auth:** Login seguro con Google (NextAuth).
- [ ] **Profile CRUD:** Carga de nombre, posición, pie hábil y foto de perfil.
- [ ] **Career Timeline:** Capacidad de agregar hitos (Club, fechas, foto de escudo).
- [ ] **Image Engine:** Proceso automático de subida, compresión y optimización de fotos.

## 2. Definiciones Técnicas Críticas
### Manejo de Imágenes
Se implementará un flujo donde cada imagen subida por el usuario sea procesada para reducir peso sin perder calidad, utilizando **Cloudinary** o el SDK de **Supabase Storage**.

### Accesibilidad y Animación
- Navegación por teclado garantizada en todas las vistas.
- Transiciones suaves de entrada (`initial`, `animate`) usando Framer Motion para dar vida al timeline.

## 3. Road to Mobile (React Native)
Aunque el foco inicial es Web, los componentes en `packages/ui` se escribirán pensando en la compatibilidad. Se evitarán librerías que dependan de manipulación directa del DOM para facilitar el uso de **React Native** en la Fase 3.

## 4. KPIs de éxito para el Desarrollador
- Lograr un puntaje de **90+ en Lighthouse** (Performance y Accesibilidad).
- Implementar los 3 temas de UI usando una única fuente de verdad (Tokens de diseño).
- Cero usos de `useMemo` manuales gracias al **React Compiler**.